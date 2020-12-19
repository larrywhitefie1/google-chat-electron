# Google Chat Desktop App

[![latest-release](https://badgen.net/github/release/ankurk91/google-chat-electron)](https://github.com/ankurk91/google-chat-electron/tags)
[![downloads](https://img.shields.io/github/downloads/ankurk91/google-chat-electron/total?cacheSeconds=1800)](https://github.com/ankurk91/google-chat-electron/releases)
[![gh-actions](https://github.com/ankurk91/google-chat-electron/workflows/release/badge.svg)](https://github.com/ankurk91/google-chat-electron/actions)
[![license](https://badgen.net/github/license/ankurk91/google-chat-electron)](https://github.com/ankurk91/google-chat-electron)
[![dependencies](https://img.shields.io/david/ankurk91/google-chat-electron?cacheSeconds=86400)](https://david-dm.org/ankurk91/google-chat-electron)

An unofficial desktop app for [Google Chat](https://chat.google.com/) build with [Electron](https://www.electronjs.org/)

### Installation

* Download the latest `.deb` file from
  the [releases](https://github.com/ankurk91/google-chat-electron/releases/latest) section.
* Install the package with this command: (correct the path)

```
sudo apt install ~/path/to/google-chat-electron-xxx-amd64.deb
```

* Relaunch the app if running already.
* Follow the same steps for updates.

### Uninstall

* Quit from app if running
* You can remove the app with this command

```
sudo apt-get remove --purge google-chat-electron
```

* The uninstallation script should remove all relevant files and folders.

### Troubleshooting

#### White screen on launch?

* Press <kbd>Ctrl</kbd> <kbd>+</kbd> <kbd>Shift</kbd> <kbd>+</kbd> <kbd>R</kbd> to reload the app.
* Check your internet connection.
* If it does not work then, reset the app data and restart.

### Supported Platforms

The app should work on Ubuntu and its derivatives.

| OS                    | Version         | Tested              |
| :---                  | :---:           |                ---: |
| Ubuntu GNOME          | 18, 20          |  :heavy_check_mark: |
| Linux Mint Cinnamon   | 20              |  :heavy_check_mark: |

### Acknowledgements

* [@robyf](https://github.com/robyf) for the initial work
* All other [contributors](https://github.com/ankurk91/google-chat-electron/graphs/contributors)

## Disclaimer

This desktop app is just a wrapper which starts a chromium instance locally and runs the actual web-app in it. All
rights to the [Google Chat](https://chat.google.com/) product is reserved
by [Google Inc.](https://en.wikipedia.org/wiki/Google)
This desktop client has no way to access none of your data.

## License

[MIT](LICENSE.txt) License
