# Memory Monitor

An accessible Windows app for finding which apps use the most RAM and which files and folders use the most storage. Supports NVDA and keyboard navigation.

[Download for Windows](https://github.com/killerprashant/memory-monitor/releases/latest/download/Memory-Monitor-windows-x64.zip)

Extract the ZIP, then open **Memory Monitor.exe**. Keep all extracted files together, including `_internal`. Requires 64-bit Windows 10 or Windows 11; Python is not required.

## Memory

- **Ctrl+1:** Memory tab. Apps appear from largest to smallest RAM use.
- **Arrow keys:** select an app or process.
- **Enter:** read details.
- **Delete:** end the selection after confirmation. Unsaved work can be lost.
- **F5:** refresh. **Ctrl+F:** search.

## Storage

- **Ctrl+2:** Storage tab. Choose All drives, one drive, or a folder, then Scan.
- **Enter:** open the selected drive or folder, or read file details.
- **Alt+Left:** go back.
- **Largest files:** list files across scanned locations from largest to smallest.
- **Ctrl+F:** search. **Ctrl+PageDown / Ctrl+PageUp:** change result pages.
- **Cancel scan:** stop and keep partial results.

Use **Ctrl+Tab** to switch tabs, **Ctrl+L** to focus the current list, **F1** for keyboard help, and **Alt+F4** to close.

## Updates

The app checks for updates when it opens. You can also choose **Help → Check for updates**. Choose **Download update** when one is available. After the download is verified, the app installs it and restarts automatically. During download, use Cancel to stop.

Diagnostic logs are saved in the **logs** folder beside the app, or in the Windows user data folder if the app folder cannot be written to.
