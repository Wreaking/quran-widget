# Quran Widget

A lightweight desktop widget that displays verses from the Quran. It runs locally on your computer and does not send any data anywhere.

---

## 1. Installation Guide
[Click me](https://drive.google.com/file/d/1PhTmJsItbinp_NPGwUdmdG3LfDm0TM4o/view?usp=sharing) for installation.
1. **Download** the Windows installer (`.exe`) from the project website.
2. **Run the installer** and follow the simple prompts.
3. **Launch the widget** from your Start menu or desktop shortcut.

That’s all – the widget will start showing verses immediately.

> On first run or after a reset the widget opens in *Random* mode. You can enable Spiritual mode later via Settings.

---

## 2. Security / Trust Note

The application is safe and works entirely on your machine. It:

* Does **not** collect or transmit any personal or usage data.
* Has no external dependencies other than the Quran data files included with the app.
* Runs completely offline.

When Windows shows an "Unknown publisher" message during install, it simply means the app is not yet digitally signed. This is normal for small independent projects and does not indicate any malicious behaviour. Rest assured, the software does not track you.

---

## 3. How to Report Issues

If you find a bug or want to suggest an improvement, please open an issue on GitHub:

1. Go to the [GitHub Issues page](https://github.com/quran-widget/quran-widget/issues).
2. Click "New issue" and describe the problem.
3. Include:
   * A screenshot if possible.
   * The steps you took leading to the issue.
   * Your Windows version (e.g. Windows 10/11).

Clear details help fix problems faster.

---

## 4. Reset Settings (Important)

To restore the widget to its original configuration, either:

* **Delete the config file** manually:
  ```powershell
  Remove-Item "$env:APPDATA\quran-widget\config.json" -Force
  ```
* **Reinstall the app** and choose to remove settings during uninstall.

Resetting returns all options to default values (Random Mode enabled, Spiritual Mode off).

---

## 5. Basic Usage

* **Move the widget**: click and drag the top bar.
* **Resize**: drag any edge or corner (only available when Wallpaper Mode is off).
* **Enable wallpaper mode**: open Settings and tick "Wallpaper Mode" – the widget becomes click-through.
* **Switch modes**: open Settings and choose *Random* or *Spiritual* under Content Mode, then save.

The top bar automatically appears when your mouse enters the widget and disappears when it leaves. In wallpaper mode the bar floats above the content without shifting anything.

Enjoy the widget as a quiet companion on your desktop.

---

## 6. Recent Changes & Notes

### Features

* **Color customization** – pick Arabic and English text colours from the settings; changes apply live and persist.
* **Arabic glow effect** on hover and optional English glow toggle for a premium look.
* **Font size sliders** with live preview and readable value display.
* **Fully interactive top‑bar** that appears on mouse enter over _any_ part of the widget (including after restarting with wallpaper mode already enabled).
* **Wallpaper mode improvements** – click‑through behaviour now works immediately on startup, and the hover‑detection system keeps the bar floating correctly.
* **“Exit completely” button** added to settings to fully close the app and clear timers.

### Fixes

* Resolved wallpaper hover bug that required a restart or extra mouse movement.
* Fixed issue where text colour settings would not update until the next restart.
* Restored pointer-events layering so the widget content is always click‑through in wallpaper mode except for the top bar.

These notes also serve as a partial changelog; for detailed history see the Git commit log or GitHub Releases page.

---


