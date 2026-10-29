<p align="center">
  <a href="https://filoshi.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/filoshi-logo-horizontal-dark.svg">
      <img src="assets/filoshi-logo-horizontal.svg" alt="Filoshi" width="264">
    </picture>
  </a>
</p>

<p align="center"><strong>The file converter that works on your PC.</strong><br>Drop anything on me.</p>

<p align="center">
  <a href="https://filoshi.com/#pricing"><strong>Get Filoshi — $29</strong></a> ·
  <a href="https://filoshi.com">filoshi.com</a> ·
  <a href="https://filoshi.com/formats">Formats</a> ·
  <a href="SUPPORT.md">Get help</a> ·
  <a href="https://github.com/OuterSpacee/Filoshi-Support/issues/new/choose">Report an issue</a>
</p>

---

This is the public support repository for **Filoshi**. Use it to report a problem, ask for a format or a feature, ask a question, or read about the product. The app's source code is not here: Filoshi is proprietary software (see [License](#license)).

## What Filoshi is

Filoshi is a desktop file converter for Windows 10 and 11. Drag a file onto the window and the character who lives in the app eats it. Pick a format, press Convert, and the new file appears next to the original, or in a folder you choose. The original is never changed.

Everything happens on your PC. The conversion engines ship inside the app (FFmpeg, ImageMagick, Pandoc, PDFium, pdfcpu and 7-Zip), so your files are never uploaded anywhere. There is no account, no cloud and no subscription.

## What it converts

**1,841 conversions passed our automated test matrix** (Windows 11, report of 2026-10-24, 0 failures). In all, the app lists 2,501 conversions from 152 input formats: the 1,841 tested ones, 220 that need a free add-on (LibreOffice or FreeCAD), and 440 that are listed but not yet covered by a test file.

| Family | Tested | Needs an add-on | Not yet tested | Examples |
|---|---:|---:|---:|---|
| Video | 896 | 0 | 0 | MP4, MOV, MKV, AVI, WebM |
| Audio | 342 | 0 | 36 | MP3, WAV, FLAC, OGG, M4A |
| Images | 420 | 0 | 342 | HEIC, RAW, PSD, WebP, AVIF, PNG, JPG |
| Documents | 123 | 71 | 8 | DOCX, PDF, EPUB, Markdown, HTML |
| Archives | 60 | 0 | 42 | ZIP, 7Z, TAR, RAR, ISO |
| 3D and CAD | 0 | 144 | 0 | STEP, STL, OBJ, GLB, DXF (with FreeCAD) |
| Email | 0 | 5 | 0 | EML (with LibreOffice) |
| Fonts | 0 | 0 | 12 | TTF, OTF, WOFF |

The full, searchable list is on [filoshi.com/formats](https://filoshi.com/formats). The counts above come from the same test data the site and the app's Formats page use, grouped the way that page groups them (GIF counts as an image).

### Optional add-ons

Two engines are too large to bundle. The app downloads them once, inside the app, the first time you need them. After that they run offline too.

- **LibreOffice**: Office documents (Word, Excel, PowerPoint, OpenDocument), for example DOCX to PDF.
- **FreeCAD**: 3D models and CAD files.

## What else is inside (Filoshi 2.0)

- **Many files at once.** Drop forty files and they go down in one gulp. Each file shows its own progress and result.
- **The file viewer.** Look before you convert: crop, rotate, resize and adjust pictures; trim video and audio, change resolution, frame rate, speed or volume; pick PDF pages. The settings are applied while it converts.
- **The PDF Suite.** Organize, merge, split, compress, protect, watermark, number and sign PDFs, and add text, pictures, highlights or drawings to a page. Saving writes a real PDF.
- **The island.** Closing the window moves Filoshi to a small pill at the top of the screen. Drop a file there, pick a format, and drag the result out. Ctrl+Alt+F opens it.
- **The taskbar buddy** (optional). Filoshi walks along the taskbar and perches on the window.
- **Characters and a wardrobe.** Seven characters and seventeen outfits. Sounds stay off unless you turn them on.

## Try it free in your browser

The home page at [filoshi.com](https://filoshi.com) converts one file right in your browser, without uploading it:

- Photos: HEIC, PNG, JPG, WebP, BMP, GIF or AVIF to JPG, PNG or WebP (up to 50 MB).
- Audio: MP3, WAV, FLAC, OGG, M4A and more (up to 100 MB).
- Video: MP4, MOV, WebM, MKV, AVI, M4V, or just the soundtrack (up to 200 MB).

Some `/convert` pages on the site also have an in-browser converter for common video and audio formats. The desktop app does everything else.

## Price

**$29, once.** One license, every 2.x update included. No subscription and no account: the license key arrives by email after checkout (payments by Polar).

[**Get Filoshi — $29**](https://filoshi.com/#pricing)

### Refund policy

All sales are final. If Filoshi doesn't work on your computer (it won't install, won't start, or can't do a conversion the site says it does) and we can't fix it with you, we refund you in full within 30 days of your purchase. Email [support@filoshi.com](mailto:support@filoshi.com). A refund turns off the license key. This does not limit any rights you have under the law where you live. Full terms: [filoshi.com/refund](https://filoshi.com/refund).

## Platforms and versions

| Platform | Version | Notes |
|---|---|---|
| Windows 10 and 11 (64-bit) | **2.0.0** (released 2026-10-27) | Everything described on this page |
| macOS | 1.0.36 | The earlier version; same license key. A Mac version of 2.0 is planned; no date yet |
| Linux | 1.0.36 | The earlier version; same license key |

Downloads are on [filoshi.com/download](https://filoshi.com/download) (you enter your license key there).

The Windows installer is not code-signed yet, so Windows SmartScreen may say "Windows protected your PC" the first time. Choose **More info**, then **Run anyway**. It installs for your user only and needs no admin rights.

## Privacy

Your files never leave your computer. Filoshi does not upload them, and the app has no tracking. The app goes online only for three things: a background license check, an update check at most once a week when it starts (you can turn this off in Settings), and downloading the LibreOffice or FreeCAD add-on when you ask for it. The website counts visits; see [filoshi.com/privacy](https://filoshi.com/privacy).

## Links

- [Formats](https://filoshi.com/formats): every conversion the app lists
- [Download](https://filoshi.com/download): installers for license holders
- [Privacy policy](https://filoshi.com/privacy)
- [Terms of service](https://filoshi.com/terms)
- [Refund policy](https://filoshi.com/refund)
- [Codec licensing](https://filoshi.com/codec-licensing): which video and audio formats may be covered by patents
- [Open-source licenses](https://filoshi.com/open-source): every bundled engine, its license and where to get its source

## How to get help or file an issue

1. Read [SUPPORT.md](SUPPORT.md). It has a short "before you file" checklist that solves the most common problems (SmartScreen, macOS Gatekeeper, missing add-ons, files too large for the browser try).
2. **Found a bug or a failed conversion?** [Open an issue](https://github.com/OuterSpacee/Filoshi-Support/issues/new/choose) and pick the matching form. Include your Filoshi version (Settings → About), your operating system, the source and target format, and the exact error text.
3. **Have a question?** Ask in [Discussions](https://github.com/OuterSpacee/Filoshi-Support/discussions).
4. **Anything about your purchase, license key or a refund?** Email [support@filoshi.com](mailto:support@filoshi.com). Never post a license key, an order number or an email receipt in a public issue.
5. **Security problem?** Do not open a public issue. See [SECURITY.md](SECURITY.md).

## License

- **The Filoshi app is proprietary software**, sold under the [terms of service](https://filoshi.com/terms). Its source code is not published. The open-source engines it bundles keep their own licenses, listed on [filoshi.com/open-source](https://filoshi.com/open-source).
- **The documents in this repository** (this README, the support guides and the issue forms) are licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0).
- The Filoshi name, logo and characters are trademarks of their owner and are not covered by CC BY 4.0.

Filoshi is made by an independent developer. Contributions to this repository are welcome as documentation fixes only; see the pull request template.
