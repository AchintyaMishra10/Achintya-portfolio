# Achintya Mishra — Portfolio

A responsive, dark portfolio for Achintya Mishra, Full Stack Developer based in Bengaluru.

## Features

- Original-color portrait and editorial typography
- About, skills, experience, education, and certifications
- Résumé that opens as a PDF and includes a clickable GitHub profile link
- Tap-to-call phone link and email link that opens a new message in the visitor's email app
- GitHub profile links, mobile navigation, and keyboard-accessible controls

## Run locally

No build step or package installation is required. With Python 3 installed, run:

```sh
python3 -m http.server 8080
```

Open http://localhost:8080 in your browser.

## Files

- `index.html` — Portfolio content and layout
- `style.css` — Responsive styles
- `script.js` — Mobile navigation
- `portrait.jpg` — Portrait photograph
- `Achintya_Mishra_Resume.pdf` — Résumé with clickable GitHub link

The site can be served by any static website host. Google Fonts requires an internet connection; system fonts are used as fallbacks.

## Publish with GitHub Pages

The site is ready to publish directly from this repository without a build step.

1. For GitHub Free, make the repository public in **Settings → General → Danger Zone → Change repository visibility**.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait for GitHub's deployment to finish. The Pages settings screen will show the live link.

Once GitHub Pages is enabled and deployed, the website URL will be:

https://achintyamishra10.github.io/Achintya-portfolio/

The `.nojekyll` file tells GitHub Pages to serve the static files directly.
