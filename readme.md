# Jer's fork of ZSA's fork of QMK Firmware

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

## Building

```sh
qmk setup jollyjerr/qmk_firmware -b firmware23

# build
make moonlander:tabb

# flash
qmk flash --keyboard moonlander --keymap tabb
```
