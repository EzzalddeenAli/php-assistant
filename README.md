<p align="center">
  <img width="200" src="https://raw.githubusercontent.com/rafajaques/php-assistant/master/app/gfx/readme/logo.png" alt="PHP Assistant Logo"/>
</p>


[![Travis Build Status](https://travis-ci.org/rafajaques/php-assistant.svg?branch=master)](https://travis-ci.org/rafajaques/php-assistant)
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/r4wsabo0ury7a5kg?svg=true)](https://ci.appveyor.com/project/rafajaques/php-assistant)
[![Latest release](https://img.shields.io/github/tag/rafajaques/php-assistant.svg)](https://github.com/rafajaques/php-assistant/releases)
[![Known Vulnerabilities](https://snyk.io/test/github/rafajaques/php-assistant/badge.svg?targetFile=app%2Fpackage.json)](https://snyk.io/test/github/rafajaques/php-assistant?targetFile=app%2Fpackage.json)
[![Dependency Status](https://david-dm.org/rafajaques/php-assistant.svg?path=app)](https://david-dm.org/rafajaques/php-assistant?path=app)
[![devDependency Status](https://david-dm.org/rafajaques/php-assistant/dev-status.svg)](https://david-dm.org/rafajaques/php-assistant?type=dev)
[![license:mit](https://img.shields.io/badge/license-mit-blue.svg)](https://opensource.org/licenses/MIT)

PHP Assistant is a cross-platform desktop app for testing PHP snippets.
Built with Electron, Node.js and HTML5/CSS/JS.
The main goal is to have a simple app to test small pieces of code without having to search for a sandbox, creating a file or opening the terminal.

<p align="center">
  <img src="https://raw.githubusercontent.com/rafajaques/php-assistant/master/app/gfx/readme/screenshot.png" alt="ScreenShot"/>
</p>

## Download

You will find the most recent releases here. Remember that PHP Assistant is still in development, so you may find bugs during its utilization. In case of problem, open an [issue](https://github.com/rafajaques/php-assistant/issues).

[![Mac OSX Download](https://img.shields.io/badge/download-Mac%20OSX-blue.svg)](https://github.com/rafajaques/php-assistant/releases/download/v0.0.11/phpassistant-0.0.11.dmg)
[![Debian/Ubuntu/Mint 32](https://img.shields.io/badge/download-Debian%2FUbuntu%2FMint%20(32)-blue.svg)](https://github.com/rafajaques/php-assistant/releases/download/v0.0.11/phpassistant-0.0.11-ia32.deb)
[![Debian/Ubuntu/Mint 64](https://img.shields.io/badge/download-Debian%2FUbuntu%2FMint%20(64)-blue.svg)](https://github.com/rafajaques/php-assistant/releases/download/v0.0.11/phpassistant-0.0.11.deb)
[![Windows 32 Download](https://img.shields.io/badge/download-Windows%20(32)-blue.svg)](https://github.com/rafajaques/php-assistant/releases/download/v0.0.11/phpassistant-Setup-0.0.11-ia32.exe)
[![Windows 64 Download](https://img.shields.io/badge/download-Windows%20(64)-blue.svg)](https://github.com/rafajaques/php-assistant/releases/download/v0.0.11/phpassistant-Setup-0.0.11.exe)

## Building

You'll need [Node.js](https://nodejs.org) installed on your computer in order to build this app.

```bash
$ git clone https://github.com/rafajaques/php-assistant/
$ cd php-assistant
$ npm install
$ npm start
```

If you don't wish to clone, you can [download the source code](https://github.com/rafajaques/php-assistant/archive/master.zip).

For easier developing you can launch the app maximized with DevTools open:

```bash
$ npm run dev
```

## Issues

If you have any problems with the app or if you have any suggestions, just open an [issue](https://github.com/rafajaques/php-assistant/issues).

## Translation

The app was released in English, Brazilian Portuguese and French.
So far, with community help, we have: French (@Johann-S), Danish (@peterbrinck), German (@ingowalther).

To translate you need to fork master branch.

In the folder `locales` you will find json files with the app strings.
Copy `en.json` file and rename it as the [language code provided by ISO](http://www.lingoes.net/en/translator/langcode.htm).

Translate the strings (the ones on the right side) and insert a reference into the list (locales variable) in `main.js` file.

After that, just send a pull request. In advance, I say thank you!

## Author

Feel free to text me on Twitter: [@rafajaques](https://twitter.com/rafajaques)

## Thanks

This project would not be possible without your help.

- [@germanocorrea](https://github.com/germanocorrea)
- [@Johann-S](https://github.com/johann-s)
