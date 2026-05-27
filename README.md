# Unity Auto Save Tool 🔄

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Platform: Unity](https://img.shields.io/badge/Platform-Unity-lightgrey.svg)

A lightweight and efficient Unity Editor extension to ensure your work is always saved securely. **Made by TALHADOGAN.**

## ✨ Added Features

### 🔄 Auto-Save Triggers
| Trigger | Description |
|:---|:---|
| **Switch to Play mode** | Saves all open scenes automatically when exiting Edit mode. |
| **Interval (timer)** | Automatically saves in the background (default: every 5 minutes). |
| **When closing the Editor** | Performs a final save sequence right before Unity closes. |

### 🎛️ Menu Options
- **`File > Save All Scenes`** → Manually save using the `Ctrl+Shift+S` shortcut.
- **`Tools > AutoSave > Save Now`** → Force save immediately.
- **`Tools > AutoSave > Toggle Auto-Save on Play`** → Enable/disable saving during Play (shows a ✓ checkmark).
- **`Tools > AutoSave > Toggle Interval Auto-Save`** → Enable/disable the timer functionality.
- **`Tools > AutoSave > Set Interval: X min`** → Quick interval options: 1 / 3 / 5 / 10 / 15 minutes.

### 💾 Settings
All preferences are saved securely in `EditorPrefs`. Your auto-save configurations remain preserved even if you completely restart the Unity Editor.

---

### 📸 Preview

<img width="377" height="206" alt="Unity Auto Save Tool Menu" src="https://github.com/user-attachments/assets/6cc14c88-1b38-4350-9fa1-8c20c2175639" />

---

## 📜 License
This project is licensed under the MIT License - see the code header for details.
