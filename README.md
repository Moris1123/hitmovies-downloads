# HitMovies downloads

Public download page for HitMovies. GitHub Pages serves the `docs/` directory from `main`.

- Windows: `docs/downloads/HitMovies-Windows-Brave.zip`
- iPhone and iPad: `docs/downloads/HitMovies.ipa` (unsigned, iOS 16+, sign with a sideloading installer)
- Optional Brave popup blocker: `docs/downloads/HitMovies-Popup-Blocker.zip`
- SHA-256 digests: `docs/downloads/checksums.json`

The web app and account server run at https://hitmovies-emerald-cinema.matajcicmoris.chatgpt.site/ . This repository contains only the download page and distributable app wrappers. No movie files, API credentials, passwords, account database, or backend source are included.

The download page preview uses a demonstration account. The iOS app was compiled by Xcode on GitHub Actions; installation and playback on a physical iPhone have not been independently tested.

Automatic time saving: iPhone v1.2 bundles an all-frame video-position observer. Brave needs the HitMovies Companion v1.1 and explicit host permissions for the current player, requested in its setup page. The ordinary website cannot read a cross-origin player without a companion. No elapsed-time estimation is used.
