Unofficial Linux desktop build of [Musify](https://github.com/gokadzev/Musify).

Built from the `linux-dist` branch of this fork (Linux runner + media_kit playback).

## Assets

- `Musify-linux-x64.tar.gz` — portable build (extract and run `musify/musify`).
- `Musify-linux-x64.AppImage` — single-file build (if produced for this release).
- `SHA256SUMS.txt` — checksums.

## Runtime dependency

The tarball does **not** bundle libmpv; install it first:

- Fedora: `sudo dnf install mpv-libs`
- Debian/Ubuntu: `sudo apt install libmpv2` (older: `libmpv1`)
- Arch: `sudo pacman -S mpv`

The AppImage bundles mpv, so no extra install is needed there.

## Not implemented (yet)

- MPRIS / media keys / desktop media notification
- Equalizer (Android-only; shows "init failed" on desktop)
- APK update prompt (Android-only)

This is an unofficial build and is not affiliated with the upstream project.
