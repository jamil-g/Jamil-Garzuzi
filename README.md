# Jamil Garzuzi — Digital Business Card

Static mobile-friendly digital business card.

## Publish on GitHub Pages

1. Upload the supplied portrait to `assets/profile.jpg` using GitHub **Add file → Upload files**. The HTML falls back to JG initials until the photo is uploaded.
2. Go to repository **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/(root)**, then click **Save**.
5. Wait for deployment, then open https://jamil-g.github.io/Jamil-Garzuzi/.

The QR code points to that public URL. It requires the qrcodejs CDN library; contact saving works without it.

## Updating details

Change links in `index.html` and the `DETAILS` object in `script.js`. The `CARD_URL` in `script.js` is the permanent QR and share target.

## Features

Responsive layout, contact links, downloadable vCard, native share, copy link, QR code, portrait with initials fallback.

This site is public, so the contact details and portrait are visible to everyone.
