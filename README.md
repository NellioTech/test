# QR Generator

A QR code generator in two versions:

| File | What it is |
|---|---|
| `QR Generator.html` | **Browser version.** Double-click it and it opens in your default browser (Safari, Chrome, Edge…). Works on Mac, Windows and Linux, offline, with nothing to install. |
| `MacQRGenerator.app.zip` | Native macOS app (SwiftUI, macOS 26+, Universal). |

## Browser version
- Type a link or text, and the QR code updates as you type
- Error correction: Low / Medium / Quartile / High
- **Save PNG** (512, 1024 or 2048 px) → saved to your Downloads folder as `QRCode.png`
- **Copy** → copies the QR image to the clipboard
- Supports Chinese and other non-ASCII text (UTF-8)
- Follows the system light/dark mode

Everything runs locally in the browser; the text you type is never sent anywhere.

QR encoding uses [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) v2.0.4 by Kazuhiko Arase (MIT license), embedded in the HTML file.
