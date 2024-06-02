# LADB

[![GitHub repo size](https://img.shields.io/github/repo-size/sekedus/ladb?label=Size)](https://github.com/sekedus/ladb) [![GitHub License](https://img.shields.io/github/license/sekedus/ladb?label=License)](https://github.com/sekedus/ladb/blob/main/LICENSE)

LADB - Local ADB Shell

Connect ADB to Android itself without Wireless Debugging or USB connection on **rooted devices**.

## Requirements

- Rooted device
- [Termux](https://github.com/termux/termux-app/releases/latest) **v0.118.0** or higher

## Installation

1. Enable Developer options & USB debugging on your device, [howto](https://developer.android.com/studio/debug/dev-options)
2. Install & open Termux
3. Grant root permission: `su`
4. Back to home directory: `exit` or <kbd>Ctrl</kbd>+<kbd>D</kbd>
5. Install `adb` & clone this repo: 
```bash
pkg install android-tools -y && cd ~/ && git clone https://github.com/sekedus/ladb.git
```
6. Install LADB: 
```bash
cd ~/ladb && bash setup && cd ~/
```

## Commands

- ladb start
- ladb stop
- ladb uninstall

## Credits

- [Termux](https://github.com/termux/termux-app)
- [Stack Overflow](https://stackoverflow.com/a/78537118/7598333)

## License

LADB is licensed under the GNU General Public License v3.0. See the [LICENSE](https://github.com/sekedus/ladb/blob/main/LICENSE) file for more details.
