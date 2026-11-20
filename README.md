# Pitwall downloads

Official builds of **Pitwall** and the auto-update manifest. Published automatically by `scripts/publish-release.*` â€” do not edit by hand.

**âž¡ Latest release:** https://github.com/sigmarift/pitwall-releases/releases/latest

Download the file for your system from the latest release, then:

## Windows
- **`Pitwall_<version>_x64-setup.exe`** â€” run it and follow the installer.

## macOS
- **`Pitwall_<version>_x64.dmg`** (Intel) / **`_aarch64.dmg`** (Apple silicon) â€” open it and drag **Pitwall** into **Applications**.

## Linux
- **`Pitwall_<version>_amd64.AppImage`** â€” the self-updating build. Make it executable and run it:
  ```
  chmod +x Pitwall_*_amd64.AppImage
  ./Pitwall_*_amd64.AppImage
  ```
- **`Pitwall_<version>_amd64.deb`** â€” Debian, Ubuntu, Mint, Pop!_OS:
  ```
  sudo apt install ./Pitwall_*_amd64.deb
  ```
- **`Pitwall-<version>-1.x86_64.rpm`** â€” Fedora, openSUSE:
  ```
  sudo dnf install ./Pitwall-*-1.x86_64.rpm
  ```

## Updating
Installed Pitwall updates itself: **Settings â†’ Updates â†’ Check for updates**, or it offers a new version on launch, verifying each update's signature before installing. On Linux the in-app update applies to the **AppImage**; for `.deb`/`.rpm` installs, install the newer file from a later release.

`latest.json` and the `.sig` files are used by the updater â€” you don't download those by hand.