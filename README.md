# Fam Angeles Portfolio

Static portfolio site (no build step). Edit `index.html`, add images to `assets/images` and videos to `assets/videos`.

## Publish on GitHub Pages
1. On github.com, create a new public repository (e.g. `famangeles-portfolio`).
2. Click "uploading an existing file" and drag in everything from this folder (index.html, README.md, assets).
3. Commit the files.
4. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main` and folder `/ (root)`, then Save.
5. After about a minute your site is live at `https://YOUR-USERNAME.github.io/famangeles-portfolio/`.

Tip: name the repository `YOUR-USERNAME.github.io` to get the shorter address `https://YOUR-USERNAME.github.io/`.

## Add your content
- Resume: replace assets/Angeles-Resume.pdf with your latest file (keep the same name). It is public once the site is live.
- Profile photo: replace assets/images/profile.jpg (about 400x530 px so it stays sharp).
- Portfolio items: edit the WORK list near the bottom of index.html. Put each image in assets/images and each video in assets/videos using the file name listed there. Only items listed there appear on the site, so add a line for each new piece. A tab with no items shows "No work added here yet."
- Notion links: only the video sub-sections still link to Notion (see LINKS in index.html). Pubmats and Email Templates now show their work directly.
- Social links: add Facebook and Instagram links in the contact card.
- GitHub rejects single files over 100 MB, so compress long videos first.
