# Download Pitwall

Pitwall is a desktop app for **Windows, macOS and Linux**. These are the official downloads, updated automatically. Pick your system below, download **one** file, install it â€” and from then on Pitwall keeps itself up to date.

### âž¡ [Get the latest version](https://github.com/sigmarift/pitwall-releases/releases/latest)

On that page, open the **Assets** list and download the one file for your computer.

---

## ðŸªŸ Windows

1. Download **`Pitwall_<version>_x64-setup.exe`**.
2. Doubleâ€‘click it to run the installer.
3. If Windows shows a blue **â€œWindows protected your PCâ€** box, click **More info â†’ Run anyway**. (This appears only because the app isnâ€™t registered with Microsoft yet â€” itâ€™s safe.)
4. Follow the steps. Pitwall then appears in your Start menu.

## ðŸŽ macOS

1. Download the `.dmg` that matches your Mac:
   - **`â€¦_aarch64.dmg`** â€” Appleâ€‘silicon Macs (M1, M2, M3, M4).
   - **`â€¦_x64.dmg`** â€” older Intel Macs.
   - *Not sure?* Apple menu () â†’ **About This Mac** shows your chip.
2. Doubleâ€‘click the downloaded `.dmg`, then drag the **Pitwall** icon into the **Applications** folder.
3. The first time you open it, **rightâ€‘click Pitwall â†’ Open â†’ Open**. (Needed once because the app isnâ€™t notarised by Apple yet.)

## ðŸ§ Linux

**Easiest â€” the AppImage (works on any distribution, and updates itself):**

1. Download **`Pitwall_<version>_amd64.AppImage`**.
2. Make it runnable and start it:
   ```bash
   chmod +x Pitwall_*_amd64.AppImage
   ./Pitwall_*_amd64.AppImage
   ```
   (Or, in your file manager: rightâ€‘click â†’ **Properties â†’ Permissions â†’ Allow executing as program**, then doubleâ€‘click it.)

**Debian, Ubuntu, Mint, Pop!_OS â€” the `.deb`:**
```bash
sudo apt install ./Pitwall_*_amd64.deb
```

**Fedora, openSUSE â€” the `.rpm`:**
```bash
sudo dnf install ./Pitwall-*-1.x86_64.rpm
```

---

## Keeping Pitwall up to date

You donâ€™t need to come back to this page. Inside the app, go to **Settings â†’ Updates â†’ Check for updates**, and Pitwall downloads and installs the newest version for you â€” it also offers the update automatically when you open the app. Nothing installs without your click.

> On Linux, the inâ€‘app update applies to the **AppImage**. If you installed the `.deb` or `.rpm`, update by downloading the newer one from the [latest release](https://github.com/sigmarift/pitwall-releases/releases/latest).

## What are the other files?

`latest.json` and the `.sig` files are used by Pitwallâ€™s updater to find and verify new versions â€” you donâ€™t need to download those yourself.

---

*These builds are published automatically. Please donâ€™t edit this page by hand.*
