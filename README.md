# Bhavira Technologies — Company Website

The official one-page website for **Bhavira Technologies Pty Ltd** — a low-cost electrode for the recovery of metals from solution (tailings, effluents, e-waste).

🔗 **Live site:** _add your URL here once published_

## What this is

A single, self-contained `index.html` — no build step, no dependencies, no frameworks. All HTML, CSS and JavaScript are in that one file. The hero animation (hexagonal metal crystals nucleating on an electrode) is rendered with the HTML canvas; fonts load from Google Fonts.

## Sections

- **Hero** — animated electrowinning crystallisation
- **Technology** — the Plastic Chip Electrode, problem vs solution
- **Proof** — measured lab results for zinc recovery
- **Metals** — the full range of target metals
- **For Mining** — the tailings / critical-minerals opportunity
- **Journey** — company milestones
- **Contact** — Bhaviratech@gmail.com

## Publishing with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then **Save**.
5. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

### Using your own domain (e.g. from Bluehost)

1. In **Settings → Pages → Custom domain**, enter your domain and save. This creates the `CNAME` file.
2. At your domain registrar (Bluehost), add DNS records pointing to GitHub Pages:
   - Four `A` records for the root domain → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One `CNAME` record for `www` → `<your-username>.github.io`
3. Wait for DNS to propagate (minutes to a few hours), then tick **Enforce HTTPS** in GitHub Pages settings.

## Editing

Open `index.html` in any text editor. Everything is in that one file:
- Update copy directly in the HTML.
- Colours are CSS variables at the top of the `<style>` block (`--graphite`, `--copper`, `--current`, etc.).
- The contact email appears in the contact section and footer.

## License

© Bhavira Technologies Pty Ltd. All rights reserved.
