# WEBP to JPEG Converter

A fast, privacy-friendly WEBP to JPEG converter web app. All processing is done locally in the browser—no server uploads required. Supports batch conversion, adjustable JPEG quality, and bulk ZIP downloads.

**Live Demo:** [https://ytmknd.github.io/WEBP2JPEG/](https://ytmknd.github.io/WEBP2JPEG/)

## Features

- **🔒 100% Client-Side:** No backend server or API required. Your images never leave your device, ensuring complete privacy.
- **🚀 Batch Processing:** Drag and drop multiple WEBP files to convert them all at once.
- **🎛️ Adjustable Quality:** Choose your preferred JPEG compression level (from 40% to 100%) before converting.
- **📦 Bulk Download:** Download converted images individually or packed into a single ZIP file.
- **🌐 Cross-Browser Support:** Includes a polyfill (`webp-hero`) to support decoding on browsers that might not have native WEBP support.

## Technologies Used

- HTML5 / CSS3 / Vanilla JavaScript (ES6+)
- [JSZip](https://stuk.github.io/jszip/) - For generating ZIP archives of converted images.
- [FileSaver.js](https://github.com/eligrey/FileSaver.js) - For triggering file and ZIP downloads.
- [webp-hero](https://github.com/chase-moskal/webp-hero) - Polyfill for WebP decoding in legacy or unsupporting browsers.

## How to Use

1. Open `index.html` in your modern web browser or visit the Live Demo.
2. Select your desired JPEG quality from the dropdown.
3. Drag and drop `.webp` files into the drop zone, or click to browse files.
4. Click the "JPEGに変換" (Convert to JPEG) button.
5. Save the converted images individually, or click "まとめてZIPダウンロード" (Download All as ZIP) to download them all at once.

## License

MIT License
