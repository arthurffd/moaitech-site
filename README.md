# Moai Data website

Static one-page site for moaitech.com. No build step: the files here are the site.

## Contents

- `index.html` – the whole page (markup and styles)
- `assets/img/` – logo, portrait, diagrams, company logos, tab icon, link-preview image
- `assets/fonts/` – Instrument Serif, Hanken Grotesk and IBM Plex Mono, served from this site
- `.nojekyll` – tells GitHub Pages to publish the files as they are

## Editing

- Text: open `index.html` and change it in place.
- Images: replace the file in `assets/img/` and keep the same file name.
- Contact address: search `index.html` for `contact@moaitech.com`.
- Contact form: messages are delivered by Web3Forms. The `access_key` in the form decides which
  inbox receives them; create a new key at web3forms.com to change it.

## Publishing on GitHub Pages

1. Create a public repository and upload everything in this folder to its root.
2. In the repository: Settings → Pages → "Deploy from a branch" → `main`, folder `/ (root)`.
3. Review the site at the temporary `github.io` address GitHub shows.
4. Only then add `moaitech.com` under Settings → Pages → Custom domain, and set the DNS
   records GitHub lists. Leave the domain's MX and TXT records untouched (they run the email).

## Fonts

The fonts are distributed under the SIL Open Font License 1.1. The licence texts are in
`assets/fonts/`.
