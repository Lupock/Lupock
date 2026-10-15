<div align="center">

<img src="icon.png" alt="Lupock" width="96" height="96">

# Lupock

**Build, record and share macros for Windows.**

[![Latest release](https://img.shields.io/github/v/release/Lupock/Lupock?label=latest&color=2f6feb)](https://github.com/Lupock/Lupock/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Lupock/Lupock/total?color=2f6feb)](https://github.com/Lupock/Lupock/releases)
[![Windows 10 and 11](https://img.shields.io/badge/Windows-10%20%7C%2011-2f6feb)](#system-requirements)

[Website](https://lupock.com) · [Download](https://github.com/Lupock/Lupock/releases/latest) · [Docs](https://lupock.com/docs) · [Changelog](https://github.com/Lupock/Lupock/releases)

</div>

---

This repository is where Lupock's installers are published. It holds release
builds and the update feed the app reads, not source code. Lupock is free to
use and closed source.

## What Lupock does

| | |
|---|---|
| **Simple Editor** | A list of commands you drag in and fill out: clicks, key presses, image and pixel checks, If blocks and loops. |
| **Recording** | Press Record, do the task once, and Lupock writes down every click and key press. |
| **Advanced Editor** | AutoHotkey v2 projects with autocomplete, a debugger, a terminal and the Lupock library. |
| **GUI Maker** | Design a settings window for your macro, so the people who run it can set it up without touching the steps. |
| **Automations** | Start macros with a hotkey from any app or on a schedule, even while Lupock sits in the tray. |
| **Community** | Browse macros other people shared, upvote and reply, and publish your own with version history. |
| **Safety checks** | Shared macros are scanned for malware, and Lupock asks before one runs programs or changes files. |

You don't need an account to build, record and play macros. Sign in only to
publish, download from the community or join discussions.

## Download and install

1. Open the [latest release](https://github.com/Lupock/Lupock/releases/latest).
2. Under **Assets**, download `Lupock_<version>_x64-setup.exe`.
3. Run it. Lupock installs for your Windows user only, so no administrator
   rights are needed.

> [!IMPORTANT]
> **"Windows protected your PC."** Until the installer is code-signed, Windows
> SmartScreen may show this warning the first time. Click **More info**, then
> **Run anyway**. Only download Lupock from this page or from
> [lupock.com](https://lupock.com).

## System requirements

- Windows 10 or Windows 11 (64-bit)
- Microsoft Edge WebView2 (built into Windows 11; the installer adds it on
  Windows 10 if it's missing)
- About 150 MB of free disk space
- An internet connection for the community and updates only

## Open-source components

Lupock includes open-source software, each under its own license. The full list
is in the app: open **About** in the sidebar, then **Open-source licenses**.

- **AutoHotkey v2** runs your macros. It's shipped unmodified as a separate
  program under the GNU General Public License v2. Its source code for the
  bundled version is attached to every release.
- **vscode-autohotkey2-lsp** by thqby powers autocomplete and diagnostics in
  the Advanced Editor, under the GNU Lesser General Public License v3. Lupock
  changes it in three marked places. The complete source of that version is
  attached to every release, and you can swap in your own build: put your
  `browserServerMain.js` in `%APPDATA%\com.lupock.app\lsp\`. The `README.txt` in
  the installed `resources\lsp` folder has the details.

## Help and feedback

- **Docs:** [lupock.com/docs](https://lupock.com/docs), also built into the app
  under **Help & Docs**.
- **Bugs and questions:** email [support@lupock.com](mailto:support@lupock.com).
  Include the version (**About** in the sidebar), what you did, what you expected, and
  a screenshot if you can.

## License

Lupock is proprietary software, free to download and use under the
[end-user license agreement](LICENSE). Its open-source components keep their
own licenses, and nothing in the agreement limits your rights under them.

<div align="center">
<sub>Copyright © 2026 money_mountain. All rights reserved.</sub>
</div>
