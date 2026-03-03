Instructions

The files for the GitHub Pages site live in this `site` subdirectory.

- `index.html` — blank-looking page that immediately sends the browser to the certificate URL. Use the page root for a QR code (e.g. `https://<your-github-username>.github.io/<repo>/`).
- `redirect.html` — alternate explicit redirect file; point a QR to it if you prefer that URL.

Deploying on GitHub Pages

1. Push this repo to GitHub (repo you created: https://github.com/Boqiboyev/app.uzbmb.uz.git).
2. In the repo settings → Pages, set the source branch to `main` and the folder to `/site` (the root of that folder) so GitHub serves its contents.
3. After Pages is active, your site will be served at https://Boqiboyev.github.io/app.uzbmb.uz/.

QR suggestions

- If you want the QR to show the download prompt: point it to `https://Boqiboyev.github.io/app.uzbmb.uz/` (which serves `index.html`).
- If you want the QR to immediately open the PDF: point it to `https://Boqiboyev.github.io/app.uzbmb.uz/redirect.html`.

Notes

- Browsers may treat programmatic downloads differently; the download is triggered from a user click on the "Allow" button to meet gesture requirements.
- The PDF itself is referenced remotely at: https://app.uzbmb.uz.github.io/cefr/certificates/12005a760392c723e80774f55949bfc0.pdf
