# BaconBootlegger's keymap for Sofle Keyboard

## Helpful Tools 

[Keymap Drawer](https://keymap-drawer.streamlit.app/)
[QMK Logo Editor](https://joric.github.io/qle/)

## Dev  Command Reference

Located in repo: https://github.com/twkm/qmk_firmware at: `/qmk_firmware/keyboards/sofle/keymaps/rgb_bacon`

### Build

```sh
qmk compile --clean -kb sofle -km rgb_bacon

```

### C Keymap to QMK JSON

Use with Keymap drawer or QMK Configurator

```sh
qmk c2json -kb sofle -km rgb_bacon -o rgb_bacon.json --no-cpp ./keymap.c
```
