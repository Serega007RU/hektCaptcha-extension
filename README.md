# <img src="public/icons/icon_48.png" width="45" align="left"> hektCaptcha Extension

Automatically solve hCaptcha using AI. Locally, with Chrome extension.

## Features

- Automatically solve hCaptcha free of charge
- No need to register or login

## Install

**Chrome Web Store:**

Download from [Chrome Web Store](https://chrome.google.com/webstore/detail/hektcaptcha-hcaptcha-solv/bpfdbfnkjelhloljelooneehdalcmljb).

**Firefox Add-ons:**

Download from [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/hektcaptcha/).

**Manual Installation:**

0. Go to [Releases](https://github.com/Wikidepia/hektCaptcha-extension/releases)
1. Download the latest `.crx` file
2. Unzip it to a folder 
3. Open `chrome://extensions/` in Chrome
4. Enable `Developer mode`
5. Click `Load unpacked` and select the folder

## How to Build

To build the extension, make sure you have Node.js installed. Then run:

```bash
npm install
npm run build           # to build Google Chrome extension
npm run build:firefox   # to build Firefox extension
```

## Acknowledgment

This project is based on the MIT-licensed [NopeCHA extension](https://github.com/NopeCHALLC/nopecha-extension). Using model from [hektCaptcha-model](https://github.com/Wikidepia/hektCaptcha-model/).

## Support this project

If you find this project useful, please consider donating:

- Ko-fi (PayPal): https://ko-fi.com/wikidepia
- TRON Address (TRX/USDT ONLY): `TDdZgEp9q1LSLiTDSMSUSVuXcHBH2uFXhV`

## Contribution

Suggestions and pull requests are welcomed!.

---

This project was bootstrapped with [Chrome Extension CLI](https://github.com/dutiyesh/chrome-extension-cli)

