# Sera Conversation Studio

A static, responsive chatbot interface demo built with plain HTML, CSS, and JavaScript. It has no build step or external runtime dependencies.

## Publish with GitHub Pages

1. Create a GitHub repository. If you want the address `https://YOUR-USERNAME.github.io/`, name it `YOUR-USERNAME.github.io`; otherwise, GitHub Pages will use a project URL such as `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
2. Unzip this project and add the **contents** of the `aura-chat-studio` folder to the root of the repository. Keep `index.html`, `.nojekyll`, and the `assets` folder together.
3. Push or upload the files to the repository's `main` branch.
4. In GitHub, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. After GitHub finishes publishing, open the Pages URL shown on that settings screen. Future commits pushed to the selected branch update the site.

No dependency installation or compilation is required. The asset paths are relative, so they work on both user/organization and project Pages URLs.

## Demo limitations

The conversation is a **scripted local demo**, not a connected AI assistant. Replies come from examples in the page's JavaScript; there is no server, model API, or chat history storage.

## Files

- `index.html` — complete page, styles, and demo behavior
- `assets/aura-portrait.webp` — persona image used by the page
- `homepage.png` — preview image
- `wrangler.jsonc` — optional Cloudflare Wrangler configuration; GitHub Pages does not use it
- `.nojekyll` — tells GitHub Pages to serve the project as-is without Jekyll processing
