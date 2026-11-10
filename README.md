# bash

GNU Bash 5.2.37, the shell most scripts ask for (#!/bin/bash)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install bash
```

| | |
|---|---|
| Version | 5.2.37 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 823812 bytes (2271273 unpacked) |
| SHA-256 of the `.tpkg` | `55ab48168da613ea8f11bf227a45738e1029cc939a7d5cd475842d88a229fac5` |

## Commands it adds

| Command | Runs |
|---|---|
| `bash` | `bin/bash` |
| `bashbug` | `bin/bashbug` |

## Download

The package file (`bash-5.2.37.tpkg`) and the sources it was built from are the assets of the
[v5.2.37 release](https://github.com/Artfical/tpkg-bash/releases/tag/v5.2.37).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `bash-5.2.37.tar.gz`

Check a download: `sha256sum bash-5.2.37.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
