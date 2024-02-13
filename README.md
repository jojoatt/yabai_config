# Yabai Tiling Window Manager Setup
![Operating System](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white)

## Installation
To install Yabai, run the following command:
```
brew install koekeishiya/formulae/yabai
```
To install JankyBorders, run the following command:

**Note**:
You need  macOS 14.0+ for this tool, if it's not the case please
comment the line that configured the border appearence in `yabairc` file
```
brew install FelixKratz/formulae/borders
```
## Setup
1. Clone config
```
git clone git@github.com:jojoatt/yabai_config.git ~/.config/yabai
```
The yabai config will be in `yabairc` file at `~/.config/yabai` path

2. That's it !


**Note**:
If you used the built-in menu bar of macOS, please comment in `yabairc` file
the line that reserved a space for custom menu bar calls `external bar`
## Usage
To start yabai:
```
yabai --start-service
```
To restart yabai:
```
yabai --restart-service
```
To stop yabai:
```
yabai --stop-service
```