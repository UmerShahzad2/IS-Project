# RogueShield – Team README

Educational Windows scareware / rogue-antivirus **simulator**.  
All scans, threats, and pop-ups are **fake**. Nothing real is infected or modified.

Default password (stop / exit): **`ItsMe2006!`**

---

## 1. What this project is

| Item | Meaning |
|------|---------|
| **RogueShield** | Main GUI (dashboard, scans, settings) |
| **RSHost** | Independent background process that owns continuous pop-ups |
| Purpose | Security-awareness training – show what scareware looks like |
| Real antivirus? | **No** |
| Modifies Windows security / files? | **No** |

Important behaviour:
- Continuous pop-ups run inside **RSHost**, not the main window.
- Closing or killing the main app **does not** stop pop-ups.
- After reboot, RSHost can auto-start (visible Startup entry).

---

## 2. Quick run from source (no build)

### Requirements
- Windows 10/11 recommended
- Python 3.10+ installed  
  https://www.python.org/downloads/  
  ✅ Check **“Add python.exe to PATH”**

### Steps
1. Extract the project ZIP.
2. Open the `RogueShield` folder.
3. Double-click:

```bat
RUN_FROM_SOURCE.bat
