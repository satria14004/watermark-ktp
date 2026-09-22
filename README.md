# Document Watermark

Mark copies of your ID and other documents before you send them. Everything runs
in your browser — files never leave your device, and there is no server, no
upload, and no network request of any kind.

## Why

When you send a scan of your ID to a landlord, a bank, or an online form, that
copy can be reused somewhere you never agreed to. Stamping it with the purpose
and the date makes a stolen copy much harder to pass off as a fresh one.

## Features

- Accepts **JPG, PNG, WebP, and PDF** — drag and drop, or pick a file
- Page navigation for multi-page PDFs
- Watermark text of your choosing, applied **once** or **repeated** across the page
- Control over typeface, size, color, opacity, and angle
- Position presets, or drag the watermark anywhere on the document
- Export as **JPEG** or **PDF**, or send straight to your printer
- Works fully offline — save the HTML file and open it with no connection

## Usage

No install, no build step, no dependencies to fetch.

**Online:** open the link above.

**Offline:** download `index.html` and open it in any modern browser. Keep it on
a USB stick if you like; it works with the network switched off.

## Privacy

Every operation happens locally in the browser. Your document is read into
memory, rendered to a canvas, and written back out on your machine. Nothing is
transmitted, stored, or logged anywhere. Verify it yourself: open the file, read
the source, or watch the network tab stay empty while you use it.

## Credits

The watermark operations code is derived from
[watermarkktp](https://github.com/watermarkktp/watermarkktp) by
[Sirilius Kevin](https://sirilius.com), used under the MIT License. This version strips the original UI and focuses on the
document-processing side with printing function.

Bundled libraries:

- [pdf.js](https://github.com/mozilla/pdf.js) 3.11.174 — Mozilla Foundation, Apache-2.0
- [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 — James Hall, MIT

## License

MIT. See [LICENSE](LICENSE) for the full text, including the original copyright
notice and DJKI registration notice from the upstream project.
