# vim

Vim 9.2: the text editor (huge feature set, no GUI; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install vim
```

| | |
|---|---|
| Version | 9.2.1254 |
| Licence | Vim |
| Upstream | https://www.vim.org |
| Needs | [`terminfo`](https://github.com/Artfical/tpkg-terminfo) |
| Needs tOS build | 616 or newer |
| Size | 10910698 bytes (33874513 unpacked) |
| SHA-256 of the `.tpkg` | `54645960d5d3e3e94ac503e5c1b08a99ff216b3b8736ae8fc2b786abc8e959d7` |

## Commands it adds

| Command | Runs |
|---|---|
| `vim` | `bin/vim` |
| `vi` | `bin/vim -N` |
| `view` | `bin/vim -R` |
| `ex` | `bin/vim -e` |
| `vimdiff` | `bin/vim -d` |
| `xxd` | `bin/xxd` |

## Download

The package file (`vim-9.2.1254.tpkg`) and the sources it was built from are the assets of the
[v9.2.1254 release](https://github.com/Artfical/tpkg-vim/releases/tag/v9.2.1254).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `vim-9.2.1254.tar.gz`
- `ncurses-6.5.tar.gz`

Check a download: `sha256sum vim-9.2.1254.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Vim. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
