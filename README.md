# heicjpg

Drop iPhone `.heic` / `.heif` photos and download JPEGs. Quality slider. One file or a zip of many.

**It runs entirely in your browser.** Nothing is uploaded, there is no backend, and there is no API key.

## Privacy

Files never leave the browser. There is no server to send them to.

## Caps

- 50 MB per file
- 20 files, 200 MB total
- Not-a-HEIC files fail with an error

Decoder is a copy of [libheif-js](https://github.com/catdad-experiments/libheif-js) (LGPL-3.0) in `vendor/`. Some odd iOS 18 HEICs may fail in the browser decoder.

## Running locally

Open `index.html` in a browser. That is the whole app.

## License

MIT — see [LICENSE](LICENSE). The vendored decoder is LGPL-3.0.

Created by [Georgi](https://x.com/georgipep) · part of [aithings.online](https://aithings.online)
