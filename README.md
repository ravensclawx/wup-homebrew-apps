# wup-homebrew-apps

The catalogue of [wup-homebrew](https://github.com/ravensclawx/wup-homebrew)'s App Store and Software Update on the
Wii U GamePad, served by GitHub Pages at `https://ravensclawx.github.io/wup-homebrew-apps`.

In the format of the Homebrew App Store's [libget](https://github.com/fortheusers/libget): `repo.json` lists the
packages, `zips/<name>.zip` holds each one's files (MD5 in `repo.json`), `packages/<name>/icon.png` its icon.

Generated, not edited: in wup-homebrew, `python3 wup-menu/tools/mkrepo.py`, then copy `wup-menu/build/repo/` here.
