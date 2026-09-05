# Ookla Speedtest

An Omarchy shell plugin that runs an Ookla Speedtest instead of the default Fast.com speedtest, featuring download and upload dials.

## Dependencies

This plugin requires the official Ookla Speedtest CLI and `jq`. On Arch Linux, you can install them via:
```bash
sudo pacman -S jq
yay -S ookla-speedtest-bin
```

## Installation

```bash
omarchy plugin add https://github.com/TheBacon00/ookla.speedtest --enable
```

## Usage

This is a panel plugin for the Omarchy Quattro shell. Once installed and enabled, it provides an internet speed test overlay that measures download and upload speeds.

## License

MIT License
