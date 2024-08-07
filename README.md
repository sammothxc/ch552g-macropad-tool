# CH552G Macropad Tool for Linux
## Description
Precompiled linux tool for remapping CH552G-based macro-pads. Most of the code was ported from https://github.com/kriomant/ch57x-keyboard-tool. Check there for usage and further documentation.

## Installation
Clone this repo and use the precompiled binary `ch552g-macropad-tool`

## Usage
### Validate the config file

```shell
./ch552g-keyboard-tool validate < your-config.yaml
```

### Upload the config to the keyboard

```shell
./ch552g-keyboard-tool upload < your-config.yaml
```

Use 'sudo' if you get 'Access denied (insufficient permissions)':

```shell
sudo ./ch552g-keyboard-tool upload < your-config.yaml
```

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
