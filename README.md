# Luban Fragrance — Website (Quick start)

This folder contains a simple static site for Luban Fragrance. You can publish it for free using GitHub Pages or Netlify.

## Files
- `index.html` — main page
- `styles.css` — styling
- `images/` — add three product photos here (`perfume1.jpg`, `perfume2.jpg`, `perfume3.jpg`)

## Quick customization (before publishing)
1. Replace product images in `images/`.
2. If you want customers to order by WhatsApp, add your phone number to WhatsApp links (we used email by default).
3. To receive form submissions by email automatically:
   - Sign up at https://formspree.io (free).
   - Create a new form and copy the form endpoint (looks like `https://formspree.io/f/XXXXXX`).
   - Replace the `action` value in the `<form>` tag in `index.html`.

## Publish on GitHub Pages (recommended, free)
1. Create a GitHub account (https://github.com/join) if you don't have one.
2. Create a new repository. For a user site, name it `yourusername.github.io`. (Or any name and enable Pages from Settings.)
3. Upload all files and the `images/` folder using "Add file" → "Upload files".
4. Commit. If repo name is `yourusername.github.io`, your site will appear at:
   `https://yourusername.github.io`
   If you used another repo, go to Settings → Pages and select the branch (usually `main`) and the folder `/ (root)`, then Save.
5. Wait a minute and open your site URL.

Alternative: Deploy with Git (on your computer)
```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Publish on Netlify (drag-and-drop)
1. Create a Netlify account (free).
2. In Netlify dashboard click "Add new site" → "Deploy manually" → drag the project folder (containing `index.html`) onto the page.
3. Netlify assigns a free subdomain and HTTPS automatically.

## Getting images
- Use clear phone photos of bottles on a plain background.
- Resize to ~1200×800 or smaller to keep site lightweight.

## Next suggestions
- Buy a domain later (optional) and point it to GitHub Pages or Netlify.
- Add a simple logo image (replace the text `.brand` or add an `img` inside header).
- When you're ready, share a phone number for WhatsApp order links (I can update links for you).
