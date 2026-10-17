Musify for Linux (unofficial desktop build)
============================================

This archive contains a release build of the Musify Flutter app for Linux x86_64.

Run it:

    ./musify/musify

Runtime dependency
------------------
Playback needs libmpv at runtime (it is NOT bundled in this tarball):

    Fedora:         sudo dnf install mpv-libs
    Debian/Ubuntu:  sudo apt install libmpv2      (older: libmpv1)
    Arch:           sudo pacman -S mpv

If libmpv is missing, playback will fail at start.

Notes
-----
- This is an unofficial build and is not affiliated with the upstream Musify project.
- No MPRIS / media keys / desktop media notification yet.
- The equalizer is Android-only and reports "init failed" on desktop.
