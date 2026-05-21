# UnityAutoSave
Unity Auto Save Tool


The script has been compiled; no errors. Here are the added features:

---

## Added Features

### 🔄 Auto-Save Triggers
| Trigger | Description |
|---|---|
| **Switch to Play mode** | Saves all open scenes when exiting Edit mode |
| **Interval (timer)** | Automatically saves every 5 minutes by default |
| **When closing the Editor** | Saves before Unity closes |

### 🎛️ Menu Options
- **`File > Save All Scenes`** → Manually save using the `Ctrl+Shift+S` shortcut
- **`Tools > AutoSave > Save Now`** → Save immediately
- **`Tools > AutoSave > Toggle Auto-Save on Play`** → Enable/disable saving during Play (shows a ✓ checkmark)
- **`Tools > AutoSave > Toggle Interval Auto-Save`** → Enable/disable the timer
- **`Tools > AutoSave > Set Interval: X min`** → Options: 1 / 3 / 5 / 10 / 15 minutes

### 💾 Settings
All preferences are saved in `EditorPrefs`; settings are preserved even if you restart Unity.

Translated with DeepL.com (free version)
