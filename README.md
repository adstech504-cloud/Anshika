# Anshika's Birthday Page

A single-page celebration site. Music is generated live in the browser
(Web Audio API), so no audio file is needed — it works as soon as the
page is hosted over HTTPS, which GitHub Pages provides automatically.

## How to host this on GitHub Pages

1. **Create a GitHub account** (skip if you already have one): https://github.com/join

2. **Create a new repository**
   - Go to https://github.com/new
   - Name it anything, e.g. `anshika-birthday`
   - Set it to **Public**
   - Click **Create repository**

3. **Upload the file**
   - On the new repo's page, click **"Add file" → "Upload files"**
   - Drag in `index.html` from this zip
   - Scroll down, click **Commit changes**

4. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab
   - In the left sidebar, click **Pages**
   - Under "Build and deployment" → "Source", choose **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → click **Save**

5. **Wait ~1 minute**, then refresh that same Pages settings page.
   You'll see a green banner with your live URL, something like:
   `https://<your-username>.github.io/anshika-birthday/`

That's it — open that link on any phone or computer. Tap the "Begin"
button (a tap/click is required to start audio, per browser rules —
this is already handled in the page).

## Updating it later
Just edit `index.html` in the repo (use the pencil icon on GitHub, or
upload a replacement file) and commit — the live site updates automatically
within a minute or two.
