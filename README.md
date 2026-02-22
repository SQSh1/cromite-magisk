# This module is deprecated for newer versions of Android. Use with caution on older versions ⚠️.
---

### Cromite WebView Magisk Module

> ⚠️ **Disclaimer**  
> This module **has not been tested on all Android devices or ROMs**. Installing it **is entirely at your own risk**.  
> If you experience boot loops or system instability after flashing, you can **remove the module via TWRP** by navigating to:  
> `/data/adb/modules/` and deleting the folder named `Cromite_WebView`.

A Magisk module that installs **Cromite WebView** (v132.0.6834.83) and sets it as the default **Android System WebView**.

This is especially useful for **rooted Android 12+ devices** looking for enhanced privacy and Chromium-based rendering improvements.

---

## Features

- Based on **Cromite**, a hardened fork of Bromite
- Improved **privacy** and **security**
- Lightweight and regularly updated
- System-wide WebView replacement without patching system partitions

---

## Installation

1. Download the `.zip` release from the [Releases](https://github.com/SQSh1/Cromite_Magisk_Module/releases) section.
2. Flash it via the **Magisk app** or **custom recovery (TWRP)**.
3. Reboot your device.
4. Cromite will now be used as your default **Android System WebView**.

> You can verify the active WebView under:  
> `Developer Options > WebView Implementation`

---

## Updates

This module uses a built-in `update.json` to support **automatic update checks** via the Magisk app.

---

## Notes

- This module **does not modify system files permanently**, so it is relatively safe to uninstall.
- Make sure to **clear cache/data of apps that rely on WebView** after installation if you notice loading issues.
- If you face **boot issues**, uninstall via TWRP as described in the disclaimer above.

---

## Credits

- Based on the **Cromite** browser project  
  [https://github.com/uazo/cromite](https://github.com/uazo/cromite)
- Inspired by the work done on **Bromite SystemWebView modules**

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](https://github.com/SQSh1/Cromite_Magisk_Module/blob/main/LICENSE) file for details.

---

**Created with love by [SQ](https://github.com/SQSh1)**  
For advanced users and educational purposes only.
