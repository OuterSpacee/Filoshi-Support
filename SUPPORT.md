# Getting help with Filoshi

There are three ways to reach us. Pick the one that fits.

| You want to | Go to |
|---|---|
| Report a bug, a failed conversion, or a problem with the website | [Open an issue](https://github.com/OuterSpacee/Filoshi-Support/issues/new/choose) |
| Ask a question, share a tip, or ask "can Filoshi do X?" | [Discussions](https://github.com/OuterSpacee/Filoshi-Support/discussions) |
| Anything about your purchase, license key, download or a refund | Email [support@filoshi.com](mailto:support@filoshi.com) |
| Report a security problem | Email, privately. See [SECURITY.md](SECURITY.md) |

Issues and Discussions are public. **Never post your license key, order number, email receipt or personal files there.** If we need one of those, we will ask you to email it.

## Before you file: a quick checklist

Most problems we hear about are one of these.

- [ ] **Windows says "Windows protected your PC" (SmartScreen).** The installer is not code-signed yet. Choose **More info**, then **Run anyway**. This is expected and is not a bug.
- [ ] **macOS says Filoshi "can't be opened" or "is damaged" (Gatekeeper).** Open System Settings → Privacy & Security, scroll down and click **Open Anyway**. If macOS still refuses, run `xattr -cr /Applications/Filoshi.app` in Terminal and open it again. The Mac version is 1.0.36.
- [ ] **An Office document, email or 3D/CAD conversion does nothing or asks for something.** Those conversions need a free add-on: **LibreOffice** (Word, Excel, PowerPoint, OpenDocument, email) or **FreeCAD** (3D models and CAD). The app downloads it once when you first need it, so you need an internet connection that one time. Check whether the add-on finished installing before you file.
- [ ] **The free try on filoshi.com refuses your file.** The browser try takes one file at a time, up to 50 MB for photos, 100 MB for audio and 200 MB for video, and only the formats it lists. Larger files and other formats need the desktop app. This is a limit, not a bug.
- [ ] **The conversion is listed but marked as not yet tested.** 440 listed conversions are not covered by our test files yet. They may still work. If one fails, please file it with the "Conversion failed" form: it helps us test it.
- [ ] **You are on the latest version.** Settings → About shows your version and lets you check for updates. Windows: 2.0.0. Mac and Linux: 1.0.36.
- [ ] **Someone already reported it.** Search the [open and closed issues](https://github.com/OuterSpacee/Filoshi-Support/issues?q=is%3Aissue) first. If you find it, add a thumbs-up or a comment with your details instead of a new issue.

## How to file a good issue

Open [a new issue](https://github.com/OuterSpacee/Filoshi-Support/issues/new/choose) and pick the form that matches:

- **Bug report**: the app crashes, freezes, looks wrong, or does something it shouldn't.
- **Conversion failed**: a specific conversion gives an error, a broken file, or a wrong result.
- **Format request**: a format or a conversion that Filoshi doesn't list yet.
- **Feature request**: an idea for the app.
- **Website issue**: something wrong on filoshi.com (a broken page, wrong information, the browser try, checkout).

Include as much of this as you can. It is the difference between a fix this week and a long back-and-forth.

1. **Filoshi version**, from Settings → About (for example 2.0.0).
2. **Operating system** and version (for example Windows 11 24H2, macOS 15, Ubuntu 24.04).
3. **Source format and target format** (for example HEIC to JPG).
4. **File size**, roughly (for example 12 MB, 2 GB).
5. **Add-ons**: whether LibreOffice or FreeCAD is installed, if the conversion needs one.
6. **The exact error text.** Copy it, don't paraphrase it.
7. **Screenshots** of the error or the wrong result, if they don't show anything private.
8. **Diagnostics** (Windows, 2.0): Settings → About → **Copy diagnostics**, then paste it into the issue. It contains versions and recent log lines, and no file names, folders or license keys. Read it before you paste.

If you can share a sample file that shows the problem and contains nothing private, say so in the issue. Do not attach anything confidential. We will never ask for your files in public.

## Response times

Filoshi is made by one independent developer, so please be patient.

- **Email** (purchases, license keys, refunds): we aim to reply within 2 business days.
- **Issues**: we read every one and aim to label it within a few business days. A fix ships in a later update; we comment on the issue when it does.
- **Discussions**: answered when we can; other users often answer first.

These are goals, not guarantees. If something blocks you from using an app you paid for, email us and say so in the subject line.

## Refunds

All sales are final. If Filoshi doesn't work on your computer (it won't install, won't start, or can't do a conversion the site says it does) and we can't fix it with you, we refund you in full within 30 days of your purchase. Email [support@filoshi.com](mailto:support@filoshi.com) from the address you bought with, or include your order number, and tell us what went wrong. Full terms: [filoshi.com/refund](https://filoshi.com/refund).

## Useful pages

- [Formats](https://filoshi.com/formats): every conversion the app lists, and which ones need an add-on
- [Download](https://filoshi.com/download): installers for license holders
- [Privacy](https://filoshi.com/privacy) · [Terms](https://filoshi.com/terms) · [Refund policy](https://filoshi.com/refund)
