# email-images

This repository is set up as a GitHub Pages site for hosting email-safe image assets over public HTTPS.

## Published URL

Because this is a project repository, GitHub Pages serves it at:

- `https://guarantormyloan.github.io/email-images/`

If you try to open `https://email-images.github.io/` directly, GitHub will show a 404 unless that domain is configured as a custom domain outside this repo.

## How to use

1. Push this repository to GitHub.
2. In the repository settings, enable GitHub Pages from the `main` branch and the root folder.
3. Use the published URLs in your email HTML so clients load the images from a public HTTPS location.

## Public image URLs

Once GitHub Pages is enabled, the images are available at URLs like:

- `https://guarantormyloan.github.io/email-images/gml_logo.png`
- `https://guarantormyloan.github.io/email-images/MTC_Logo.png`
- `https://guarantormyloan.github.io/email-images/inbound-img.png`

## Email client note

Most email clients only render remote images when the file is reachable from a public HTTPS URL and the image format is supported by the client. PNG and ICO assets in this repo are suitable for broad compatibility.