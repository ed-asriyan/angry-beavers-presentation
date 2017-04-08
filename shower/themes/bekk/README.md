# BEKK theme for Shower

**Welcome to be BEKK Shower theme!**

The BEKK shower theme is a fork of the [Ribbon](http://github.com/shower/ribbon) theme for [Shower](https://github.com/shower/shower/) presentation engine. It is mainly used by employees of [BEKK Consulting AS](http://bekk.no/) and my own presentations run by BEKK.

## Usage

If you want to install the BEKK shower theme separately you can download the [theme archive](https://github.com/tmn/shower-bekk/releases/download/1.0.0/shower-bekk.zip) or install the package:

	npm install shower-bekk

## Features

All theme’s features are demonstrated in the [index.html](index.html) file. Use it as a reference while building your presentation. See more detailed [features overview](https://github.com/shower/shower/blob/master/docs/features-en.md).

## Ratios

The BEKK shower theme supports two slide ratios: wide 16×10 (default) and taller 4×3. To change the slide’s ratio include one of the pre-built `screen-16x10.css` or `screen-4x3.css` files in the `<head>` of your presentation.

## PDF

The BEKK shower theme could be exported to PDF by printing it from the list mode in Chrome or Opera browsers. See [printing documentation](https://github.com/shower/shower/blob/master/docs/printing-en.md) for more options.

## Development

If you want to adjust theme for your needs:

1. Fork this repository and clone it to your local machine.
2. Install dependencies: `npm install`.
3. Start a local server with watcher: `npm run dev` or just `gulp` if you have it installed globally.
4. Edit your files and see changes in the opened browser.

To take part in BEKK shower theme development please read [contributing guidelines](CONTRIBUTING.md) first and [file an issue](https://github.com/tmn/shower-bekk/issues/new) before sending any pull request.

---
Licensed under [MIT License](LICENSE.md).
