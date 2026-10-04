# LaunchPad releases

Download **LaunchPad** for Windows: [LaunchPad-Setup.exe](https://github.com/Bafliko/launchpad-releases/releases/latest/download/LaunchPad-Setup.exe)

All other apps (PDF Forge, QR Forge, ytdl, USB MultiCopy, Phantom) are installed from inside LaunchPad.

---

This repository only hosts built binaries. The source code is private.

- `apps.json` is the app catalog that LaunchPad reads. It is **signed**, so editing it by hand breaks
  verification and LaunchPad will ignore it. It is updated only by `scripts/release.js`.
- Releases tagged `v<version>` are LaunchPad itself, and only those are marked "latest".
- Releases tagged `<app>-v<version>` are app zips, published with `--latest=false`.
