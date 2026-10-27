<p align="center">
  <img src="icon.png" width="112" alt="TopNotch" />
</p>

<h1 align="center">TopNotch</h1>

<p align="center">
  An interactive notch for Windows 11: music, calendar, focus, health, AI and your PC's vitals at the top of your screen.
</p>

<p align="center">
  <a href="https://github.com/ShageeshanT/topnotch-releases/releases/latest"><b>⬇&nbsp; Download the latest version</b></a>
</p>

---

This repository holds TopNotch's **downloads** and the **update feed** that the app checks. There's no source code here.

## Install

1. Download **`TopNotch_x.y.z_x64-setup.exe`** from the [latest release](https://github.com/ShageeshanT/topnotch-releases/releases/latest).
2. Run it. It installs for your user, so no admin rights are needed.
3. If Windows SmartScreen says "Windows protected your PC", click **More info → Run anyway**. The app isn't code-signed yet.

Prefer no installer? Download **`TopNotch_x.y.z_x64_portable.exe`** and run it from anywhere. The portable edition can't update itself; download the new one when an update comes out.

## Updates

From version 0.4.0, TopNotch updates itself:

- It checks for a new version when it starts and every few hours. Open **Settings → About** to check by hand.
- When an update is ready, the notch tells you. Click **Update** and TopNotch downloads it, installs it and reopens. Your notes, todos, settings and keys stay as they are.
- Turn on **Install updates automatically** in Settings → About to skip the click.

Every update is signed, and TopNotch refuses an update whose signature doesn't match.

Each release lists its files and their **SHA-256** checksums (`SHA256SUMS.txt`), so you can check a download.

**Requirements:** Windows 11 (64-bit) with WebView2 (built in).
