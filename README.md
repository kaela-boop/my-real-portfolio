# MaverickOps — Portfolio of Work

An interactive, single-page portfolio of MaverickOps engagements — operations
strategy, systems architecture, and organizational infrastructure. Navigate by
engagement in the sidebar; each engagement has its own page with expandable
project ("systems built") cards, results, and a contact / booking page.

## What to deploy

**`index.html`** — a fully self-contained build. Fonts, logo, JavaScript, and
all styling are inlined into this one file, so it works offline and has **no
external dependencies and no relative asset paths**. Nothing else needs to be
uploaded for the site to run.

> `MaverickOps Portfolio.html` is the same build under its original name.
> `index.html` is a copy with a clean, URL-safe filename — deploy that one.
> The `*.dc.html` file and the `assets/` and `support.js` files are **source**,
> used to regenerate the build; they are not needed for hosting.

## Deploying on GitHub Pages

1. Create a repository and upload **`index.html`** to the repository root
   (you can drag it straight into the GitHub web UI, or commit it).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set the branch to **`main`** and the folder to **`/ (root)`**, then **Save**.
5. Wait ~1 minute. Your site publishes at:
   `https://<your-username>.github.io/<repository-name>/`

Because `index.html` is the default document, the bare URL loads the portfolio
directly — no path or subfolder needed.

### Custom domain (optional)

To serve it from your own domain (e.g. `portfolio.maverickops.co`):

1. In **Settings → Pages → Custom domain**, enter the domain and save (this adds
   a `CNAME` file to the repo).
2. At your DNS provider, add a `CNAME` record pointing the subdomain to
   `<your-username>.github.io`.
3. Once DNS resolves, enable **Enforce HTTPS**.

## Updating the content

Edit the source Design Component (`MaverickOps Portfolio (Web).dc.html`), then
re-export the standalone build and replace `index.html`. Editing the compiled
`index.html` by hand is not recommended — it's minified and inlined.

## Notes

- **Contact:** Kaela Hargis, Founder & Systems Strategist — kaela@maverickops.co
- **Booking:** https://maverickops.co/get-started
- This portfolio is a curated selection of work, not an exhaustive list.
