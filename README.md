# PixelDrainBypass

A userscript that automatically redirects PixelDrain URLs to a faster mirror. It intercepts requests to pixeldrain.com and redirects them to an alternative server for faster downloads.

## Features

- ⚡ Automatic redirection to a faster mirror
- 🚀 Improves download speeds from PixelDrain
- 🛡️ Simple and lightweight implementation
- 🔄 Works immediately upon page load

## How It Works

The script detects when you visit a pixeldrain.com file URL (format: `https://pixeldrain.com/u/FILE_ID`), extracts the file ID, and automatically redirects you to `https://pd.cybar.xyz/FILE_ID` which serves the same content but potentially with faster speeds.

## Installation

1. Install a userscript manager:
   - [Tampermonkey](https://www.tampermonkey.net/) (Recommended)
   - [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
   - [Violentmonkey](https://violentmonkey.github.io/)

2. Install the script:
   - [Install from Greasy Fork](https://greasyfork.org/en/scripts/532142-pixeldrain-bypass) (Recommended)
   - Create a new script in your userscript manager and copy the contents of [`PixelDrainBypass.js`](https://github.com/nazdridoy/PixelDrainBypass/blob/main/PixelDrainBypass.js)

## Usage

Simply visit any PixelDrain file URL (https://pixeldrain.com/u/*), and the script will automatically redirect you to the faster mirror.

No configuration or user interaction is required - it works immediately after installation.

## License

MIT License - see the license section in [PixelDrainBypass.js](https://github.com/nazdridoy/PixelDrainBypass/blob/main/PixelDrainBypass.js) for details.

## Credits

Created by [nazdridoy](https://github.com/nazdridoy)

## Support

If you encounter any issues or have suggestions:
- [Open an issue](https://github.com/nazdridoy/PixelDrainBypass/issues)
- [Submit a pull request](https://github.com/nazdridoy/PixelDrainBypass/pulls)
