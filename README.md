# mikuremu.jp

Static one-page company website for **mikuremu** (https://mikuremu.jp), intended for GitHub Pages.

## Files
- `index.html` – the page (Japanese primary, English section at `#en`)
- `style.css` – styles (system fonts only, no external assets, no JavaScript)
- `CNAME` – custom domain for GitHub Pages (`mikuremu.jp`)

## Contact email (PLACEHOLDER)
`contact@mikuremu.jp` is a **placeholder**. It appears in exactly one place: the
`<p class="email">` line in the Contact section of `index.html` (marked with a
`CONTACT EMAIL` comment). Update both the `mailto:` link and the visible text
there once the real mailbox is set up.

## Deploy to GitHub Pages
1. Push these files to the root of a repository (e.g. `main` branch).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Custom domain: `mikuremu.jp` (already set via `CNAME`); enable *Enforce HTTPS*.
4. DNS for the apex domain: A records to `185.199.108.153`, `185.199.109.153`,
   `185.199.110.153`, `185.199.111.153` (and optionally a `www` CNAME to `<user>.github.io`).

## Local preview
Open `index.html` directly in a browser — no server or build step required.
