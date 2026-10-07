# WINOS beta

**Play your Windows PC's sound on your Sonos speakers** over your home Wi-Fi. Games, videos, Spotify and calls all work. No cables, no account, nothing in the cloud.

This is a public test version. Thanks for trying it!

## Download

**[Download the latest beta](https://github.com/Kyberverse/winos-beta/releases/latest)**: get `WINOS-Setup-beta1.exe` from the release.

- **Windows:** Windows 10 (version 2004 or newer) or Windows 11, 64-bit.
- **Speakers:** a Sonos speaker on the S2 app, on the same network as your PC.
- **Cost:** free during the beta, and no key is needed. The beta works until 31 December 2026.

## Install

1. Open `WINOS-Setup-beta1.exe`.
2. Windows shows "Windows protected your PC" because the beta isn't code-signed yet. Click **More info**, then **Run anyway**.
3. Choose your options and click **Install**. It installs for your Windows account only, without administrator rights.
4. If Windows Firewall asks about WINOS, allow it on **Private networks**.
5. Pick your speaker and click **Connect**.

To uninstall: Windows Settings › Apps › Installed apps › WINOS › Uninstall.

To check the download is the real file, its SHA-256 checksum is listed in the release notes. In PowerShell, run `Get-FileHash .\WINOS-Setup-beta1.exe`.

## Feedback

Tell us what works and what doesn't, especially if you have a Sonos speaker other than a Sonos One (Arc, Beam, Era, Five, Move, Roam, or S1 speakers).

- In WINOS, open **Diagnostics** and click **Copy report**. It contains no passwords, keys or stream links.
- Use the **Send feedback** link at the bottom of the WINOS side menu, or open an [issue](https://github.com/Kyberverse/winos-beta/issues) here.

## Privacy

Sound goes straight from your PC to your speakers over your local network. WINOS has no accounts, no tracking and no analytics, and it doesn't contact the internet.

---

WINOS is an independent product. It is not affiliated with, endorsed, sponsored or approved by Sonos, Inc. Sonos is a trademark of Sonos, Inc. The beta is provided as is, without warranty. This repository only hosts the beta installer; WINOS is not open source.
