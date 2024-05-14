# CH552G Macropad Tool for Linux
## Description
Precompiled linux tool for remapping CH552G-based macro-pads. Most of the code borrowed/ported from https://github.com/kriomant/ch57x-keyboard-tool. Check there for documentation/installation/usage.

## Validate the config file

```shell
./ch552g-keyboard-tool validate < your-config.yaml
```

## Upload the config to the keyboard

```shell
./ch552g-keyboard-tool upload < your-config.yaml
```

Use 'sudo' if you get 'Access denied (insufficient permissions)':

```shell
sudo ./ch552g-keyboard-tool upload < your-config.yaml
```

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
