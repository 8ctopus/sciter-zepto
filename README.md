# sciter zepto demo app

This is a [sciter.js](https://sciter.com/) demo app that explores the use of [zepto](https://zeptojs.com/) as a jQuery alternative.

jQuery does not work in Sciter as jQuery was designed to support specific browsers. Zepto is a minimalist JavaScript library with a largely jQuery-compatible API. If you use jQuery, you already know how to use Zepto.

## demo

- git clone the repository
- on Linux/Mac `chmod +x install.sh start.sh`
- run `install.bat` (Win) or `./install.sh` (Linux/Mac) to download the latest sciter binaries and the sciter package manager
- install packages `php bin/spm.phar install`
- run `start.bat` (Win) or `./start.sh` (Linux/Mac)

## debug app

- start `inspector.exe`
- inside the `scapp.exe` window click `CTRL + SHIFT + I` to connect to the inspector
- click `CTRL + SHIFT + left click` to inspect an element
