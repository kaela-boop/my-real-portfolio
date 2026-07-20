# MaverickOps — Portfolio of Work

An interactive, mobile-responsive portfolio of MaverickOps engagements:
operations strategy, systems architecture, and organizational infrastructure.

## Deploying to GitHub Pages

Everything is contained in a single file — **`index.html`**. Fonts, logo,
styling, and JavaScript are all inlined, so there are **no other files to upload
and no folders to include**. Do not upload `assets/`, `support.js`, or the
`.dc.html` source — they are not needed and can cause confusion.

1. In your repository, upload **only `index.html`** (and this `README.md`) to the
   root. If GitHub asks about overwriting an existing `index.html`, confirm the
   replace.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select branch **`main`** and folder **`/ (root)`**, then **Save**.
5. Wait about a minute. The site publishes at:
   `https://<your-username>.github.io/<repository-name>/`

Because the file is named `index.html`, the bare URL loads the portfolio
directly.

## Troubleshooting

- **Blank page or broken layout:** make sure the uploaded file is named exactly
  `index.html` (all lowercase, no spaces) and sits at the repository root — not
  inside a subfolder.
- **Old version still showing:** hard-refresh (Ctrl/Cmd + Shift + R). GitHub
  Pages can cache for a minute or two after an update.
- **404:** confirm Pages is enabled and pointing at the branch/folder where
  `index.html` lives.

## Updating

`index.html` is a compiled build — don't hand-edit it. To change content, the
source is regenerated and `index.html` re-exported, then re-uploaded.

## Contact

- Kaela Hargis — Founder & Systems Strategist
- kaela@maverickops.co
- Book a call: https://maverickops.co/get-started
