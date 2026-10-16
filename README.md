<!-- BEGIN public-repo-header -->
<div align="center">

# Climb Session PWA

<a href="https://github.com/blackmath88/airtime"><img alt="Primary language: HTML" src="https://img.shields.io/badge/language-HTML-526078?style=flat"></a>
<a href="https://github.com/blackmath88/airtime#readme"><img alt="README" src="https://img.shields.io/badge/docs-readme-16796f?style=flat"></a>
<a href="https://github.com/blackmath88/airtime/commits/main"><img alt="Last commit" src="https://img.shields.io/github/last-commit/blackmath88/airtime?style=flat&amp;color=737373"></a>

</div>
<!-- END public-repo-header -->

A single-session climbing timer driven by JSON.

## Run locally

You need a local web server because service workers do not run from `file://`.

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Publish on GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose `main` and `/root`.
6. Open the published GitHub Pages URL.
7. In Chrome or Edge, choose **Install app** or **Add to Home screen**.

## Customize

Edit `session.json`, or use **Edit JSON** inside the app.

The app stores live state locally in the browser and restores after reload.
