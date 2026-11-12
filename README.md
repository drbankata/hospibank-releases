# Hospibank releases

Signed update files for Hospibank, read by **Hospibank Setup** ("Check for updates") on the hospitals' servers.

- `index.json`: the list of the newest update for each edition, signed in `index.sig` with the seller's key.
- `files/*.bankupdate`: the update files, each signed on its own.

Hospibank Setup uses a file only when both signatures check out. This repository holds no code, no keys and no hospital data.
Published with `release.ps1` from the Hospibank source.
