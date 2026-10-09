# Lumen AI Studio

A browser-based creative AI studio with image generation, idea expansion, prompt building, local image downloads, and optional OpenAI API-key support.

## Publish on GitHub Pages

1. Create a new GitHub repository and upload the contents of this folder.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. Push to `main`. The included workflow publishes the site automatically.

Your site will be available at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## API-key note

Keys are saved in the browser's local storage and sent directly from the visitor's browser to the selected provider. Do not use a shared production key in this public client-only app. For a production app, move API requests into a server-side service or Cloudflare Worker and keep keys in server-side secrets.
