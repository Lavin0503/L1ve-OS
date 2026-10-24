<p align="center">
  <img src="logo.svg" alt="L1VE OS logo" width="120">
</p>

<h1 align="center">L1VE OS</h1>

<p align="center">
  A free desktop that boots like a real machine. Draggable icons, a file manager, a taskbar, and an app store, in a single window.
</p>

<p align="center">
  <a href="https://github.com/Lavin0503/L1ve-OS/releases"><b>⬇ Download Releases</b></a>
  ·
  <a href="https://lav1n.is-a.dev/L1ve-OS/">Run it in your browser</a>
</p>

---

## ⬇ Download

Binaries are provided directly via GitHub Releases. Download the build for your operating system:

| Platform | Download Link | File Type |
| :--- | :--- | :--- |
| **Windows** | [Download L1ve.OS.exe](https://github.com/Lavin0503/L1ve-OS/releases/download/v2.0.0/L1ve.OS.exe) | `.exe` |
| **macOS** | [Download L1ve_OS_MacOS.dmg](https://github.com/Lavin0503/L1ve-OS/releases/download/v2.0.0/L1ve_OS_MacOS.dmg) | `.dmg` |
| **Linux** | [Download L1VE-OS-LINUX.AppImage](https://github.com/Lavin0503/L1ve-OS/releases/download/v2.0.0/L1VE-OS-LINUX.AppImage) | `.AppImage` |

You can also view all assets on the [Releases Page](https://github.com/Lavin0503/L1ve-OS/releases). No install is needed if you just want to try it: the [website](https://lav1n.is-a.dev/L1ve-OS/) runs the same OS in your browser.

---

### ⚠️ First-Launch Security Warnings

Because L1VE OS is an independent, free open-source project without a paid corporate certificate, your operating system may prompt you on the first launch.

#### Windows (SmartScreen)
1. If Windows shows a *"Windows protected your PC"* prompt, click **More info**.
2. Click **Run anyway**.

#### macOS (Gatekeeper)
1. Open the `.dmg` and drag **L1ve OS** into your **Applications** folder.
2. Launch the app from Applications. If blocked with *"Apple could not verify L1ve OS"*, click **Done** (do *not* click Move to Bin).
3. Open **System Settings → Privacy & Security**.
4. Scroll down to the **Security** section and click **Open Anyway**.

#### Linux (AppImage)
1. Make the file executable: right-click it, open **Properties → Permissions**, and allow executing it as a program. Or run `chmod +x L1VE-OS-*.AppImage` in a terminal.
2. Double-click it, or run `./L1VE-OS-*.AppImage`.
3. If nothing happens, install FUSE 2: `sudo apt install libfuse2` (on Ubuntu 24.04 the package is `libfuse2t64`).
4. If you see a sandbox error on Ubuntu 24.04 or newer, launch it with `./L1VE-OS-*.AppImage --no-sandbox`.

---

## ✨ Features

- **Boots like a real machine:** a QEMU-style startup with a BIOS banner, a GRUB menu (normal, recovery mode, fast boot), a kernel log and service list, then an animated logo splash. Press **Esc** to skip it.
- **First-time setup:** a Windows-style wizard for your name, theme, accent colour, wallpaper, optional PIN and preferences
- **Lock screen:** swipe up (or click, scroll, or press Enter) to reach sign-in, with optional PIN
- **Draggable desktop icons** that snap to a grid and remember their position
- **File manager** with folders, search, cut/copy/paste, rename, drag and drop, and file properties
- **Recycle Bin** with restore, delete forever, and empty
- **Taskbar** with pinned apps, folders, and files, reorderable by dragging, plus a running-app indicator
- **Start menu** with app search (**Ctrl+K**), right-click menus, and snap-to-edge windows
- **L1VE Store** with free apps: Snake, Tic-Tac-Toe, Memory Match, Typing Test, Piano, Focus Timer, Sticky Notes, Unit Converter, Password Maker, Palette, and more
- **Built-in apps:** Notes, Terminal, Calculator, Paint, Browser, Task Manager, To-Do, Calendar, Clock, Settings
- **Personalization:** dark and light themes, accent colours, wallpapers, a desktop clock widget, PIN sign-in, reduce motion

## 💾 Your data

Files and settings are saved locally on your device, so your desktop is how you left it. The **Settings → Reset** option erases it.

## 🛠 Build it yourself

The desktop apps are the same single `index.html` wrapped in [Electron](https://www.electronjs.org/).

```bash
npm install
npm start        # run it locally
npm run dist     # build the Linux AppImage into dist/
```

A GitHub Actions workflow builds the AppImage automatically. Run it from the **Actions** tab, or push a version tag such as `v2.1.0` to attach the build to a release.

## 🔗 Links

- Releases: https://github.com/Lavin0503/L1ve-OS/releases
- Website: https://lav1n.is-a.dev/L1ve-OS/
- More projects: https://lav1n.is-a.dev

## 📄 Testers - THIS WOULDN'T BE HERE WITHOUT YOU GUYS :D
TYSM 
@anki201566
@7256
@boinger42
