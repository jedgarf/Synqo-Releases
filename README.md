<div align="center">

<img src="icon.png" alt="Synqo" width="112" height="112" />

# Synqo

**Local-first, zero-cloud file transfer.** Send files between your computers and phones over Wi-Fi or a hotspot. Nothing goes through the internet.

[**⬇ Download the latest release**](https://github.com/jedgarf/Synqo-Releases/releases)

</div>

---

This repository hosts the installable releases of Synqo for **macOS, Windows, Linux and Android**. See every version and what changed on the [Releases page](https://github.com/jedgarf/Synqo-Releases/releases).

Desktop releases are tagged `desktop-v<version>` and Android releases `android-v<version>`.

## What Synqo does

- **Nearby radar:** devices running Synqo on the same network appear on their own
- **No shared Wi-Fi needed:** works on a phone or laptop hotspot, and you can always **Connect by IP**
- **Fast:** files stream straight from one device to the other, even multi-gigabyte videos
- **You decide:** every incoming transfer asks first; devices you trust can be auto-accepted
- **Private:** no account, no cloud, no internet connection required
- History, trusted devices, light and dark mode

## Which file do I need?

| Device | File |
| --- | --- |
| Mac with Apple silicon (M1 and newer) | `Synqo-<version>-arm64.dmg` |
| Mac with Intel | `Synqo-<version>-x64.dmg` |
| Windows PC (most PCs) | `Synqo-Setup-<version>-x64.exe` |
| Windows on ARM (e.g. Snapdragon laptops) | `Synqo-Setup-<version>-arm64.exe` |
| Linux | `Synqo-<version>-x86_64.AppImage`, `Synqo-<version>-arm64.AppImage` or `synqo-desktop_<version>_amd64.deb` |
| Android phone or tablet | `Synqo-v<version>.apk` |

An iPhone and iPad version is not available yet.

## Installing

### macOS

1. Open the `.dmg` and drag **Synqo** into **Applications**.
2. The first time, macOS says it can't verify the developer. Open **System Settings › Privacy & Security** and click **Open Anyway** next to Synqo.
3. Allow **Local Network** access when asked. Synqo needs it to find other devices.

### Windows

1. Run the `Setup` `.exe`. If SmartScreen appears, click **More info › Run anyway**.
2. When Windows Defender Firewall asks, allow Synqo on **Private** and **Public** networks. Hotspots usually count as Public.

### Linux

- **AppImage:** make it executable (`chmod +x Synqo-*.AppImage`) and run it.
- **Debian/Ubuntu:** `sudo apt install ./synqo-desktop_*_amd64.deb`

### Android

1. Download `Synqo-v<version>.apk` from the [latest Android release](https://github.com/jedgarf/Synqo-Releases/releases) on your phone.
2. Open the file. If asked, allow your browser or file manager to install apps.
3. If Google Play Protect warns you, tap **More details › Install anyway**. It shows this for apps installed outside the Play Store.

Received files are saved in **Downloads › Synqo** on Android and in the **Synqo** folder inside Downloads on computers.

**Updating:** install the new version over the old one. Your history and trusted devices stay.

## Not on the same Wi-Fi?

1. Turn on a hotspot on one device (your phone, or **Settings › Network › Mobile hotspot** on Windows) and connect the other device to it.
2. Open Synqo on both. They should appear within a few seconds.
3. If not, tap **Connect by IP** and type the address shown on the other device.

## Problems or ideas?

Open an [issue](https://github.com/jedgarf/Synqo-Releases/issues) and include your device, operating system and Synqo version.
