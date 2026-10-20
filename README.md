# PRISM Display Studio

Windows display management with profiles, monitor arrangement, color controls,
taskbar preferences, and global shortcuts.

## Download

Get the [latest release](https://github.com/friends-make-tools/prism-releases/releases/latest).

- **Setup-x64.exe**: recommended per-user installation, shortcuts, and uninstaller.
- **x64.exe**: standalone desktop executable.
- **Portable-x64.zip**: extract the whole `Prism` folder and open `Prism.exe`.

Windows 10 1809+ x64 or Windows 11 is required. No Python installation is needed.
Setup can install Microsoft WebView2 Runtime when it is missing; the standalone
and portable editions require WebView2 to be present already.

## Updates

Open **Settings → Updates** in PRISM to check for a newer stable release,
download its verified package, and choose **Install and restart**. Downloads
are checked against the published manifest's size and SHA-256 hash. Installation
is always your choice. Profiles and settings stay in `%LOCALAPPDATA%\Prism`.

This repository contains official release downloads and the public update feed.
Application source is maintained separately in a private repository. Release
packages include dependency notices and build provenance. The current packages
are unsigned; Windows may display an unknown-publisher warning.
