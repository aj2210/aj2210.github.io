# aj2210.github.io

Personal site — <https://aj2210.github.io>

Single self-contained `index.html`. No build step, no dependencies except Google Fonts.
Edit and push; GitHub Pages redeploys in about a minute.

## Custom domain

This repo previously contained a `CNAME` for `anujjain.me`. That domain no longer
resolves, and GitHub Pages honours the CNAME regardless — which made
`aj2210.github.io` redirect to a dead host. The file has been removed so the
github.io address serves directly.

To use a custom domain again: re-register it, point a CNAME record at
`aj2210.github.io`, then set it under Settings → Pages.
