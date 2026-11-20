# Download Pitwall

Pitwall is a desktop app for **Windows, macOS and Linux**. These are the official downloads, updated automatically. Pick your system below, download **one** file, install it — and from then on Pitwall keeps itself up to date.

### ➡ [Get the latest version](https://github.com/sigmarift/pitwall-releases/releases/latest)

On that page, open the **Assets** list and download the one file for your computer.

---

## 🪟 Windows

1. Download **`Pitwall_<version>_x64-setup.exe`**.
2. Double‑click it to run the installer.
3. If Windows shows a blue **“Windows protected your PC”** box, click **More info → Run anyway**. (This appears only because the app isn’t registered with Microsoft yet — it’s safe.)
4. Follow the steps. Pitwall then appears in your Start menu.

## 🍎 macOS

1. Download the `.dmg` that matches your Mac:
   - **`…_aarch64.dmg`** — Apple‑silicon Macs (M1, M2, M3, M4).
   - **`…_x64.dmg`** — older Intel Macs.
   - *Not sure?* Apple menu () → **About This Mac** shows your chip.
2. Double‑click the downloaded `.dmg`, then drag the **Pitwall** icon into the **Applications** folder.
3. The first time you open it, **right‑click Pitwall → Open → Open**. (Needed once because the app isn’t notarised by Apple yet.)

## 🐧 Linux

**Easiest — the AppImage (works on any distribution, and updates itself):**

1. Download **`Pitwall_<version>_amd64.AppImage`**.
2. Make it runnable and start it:
   ```bash
   chmod +x Pitwall_*_amd64.AppImage
   ./Pitwall_*_amd64.AppImage
   ```
   (Or, in your file manager: right‑click → **Properties → Permissions → Allow executing as program**, then double‑click it.)

**Debian, Ubuntu, Mint, Pop!_OS — the `.deb`:**
```bash
sudo apt install ./Pitwall_*_amd64.deb
```

**Fedora, openSUSE — the `.rpm`:**
```bash
sudo dnf install ./Pitwall-*-1.x86_64.rpm
```

---

## Keeping Pitwall up to date

You don’t need to come back to this page. Inside the app, go to **Settings → Updates → Check for updates**, and Pitwall downloads and installs the newest version for you — it also offers the update automatically when you open the app. Nothing installs without your click.

> On Linux, the in‑app update applies to the **AppImage**. If you installed the `.deb` or `.rpm`, update by downloading the newer one from the [latest release](https://github.com/sigmarift/pitwall-releases/releases/latest).

## What are the other files?

`latest.json` and the `.sig` files are used by Pitwall’s updater to find and verify new versions — you don’t need to download those yourself.

---

*These builds are published automatically. Please don’t edit this page by hand.*
