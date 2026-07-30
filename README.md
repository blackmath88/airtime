# Climb Session PWA

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
