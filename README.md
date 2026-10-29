# Animal Welfare Hub Köln

The website for the Animal Welfare Hub: coworking in Cologne for people working on their own projects for food system change.

Plain static HTML, no build step. `index.html` is the page, `impressum.html` and `datenschutz.html` are the legal pages.

## Before linking the page anywhere

1. **Impressum address.** `impressum.html` shows only name and city for now. A full address (a c/o address works, a Postfach does not) gets added once there is one to use, for example the hub's own rooms.

## Logo

The mark is a pig's hoof print whose two toes also read as the two spires of the Cologne Cathedral. It is inline SVG in the header, `favicon.svg` for the browser tab, and `og.png` (1200×630) as the preview image when the link is shared. The `og:image` and `og:url` addresses in `index.html` use the domain, so update them if it ever changes.

## Sign-ups

The form posts to Formspree (`FORM_ENDPOINT` near the bottom of `index.html`), which forwards each sign-up by email.

## Hosting

GitHub Pages, from the `main` branch, root folder: Settings → Pages → Deploy from a branch.

The site lives at https://animalwelfarehub-koeln.de. The `CNAME` file holds that domain for GitHub Pages; the DNS at the registrar points the bare domain at GitHub's four A records (185.199.108.153 to 185.199.111.153) and `www` by CNAME at `fburgerdev.github.io`.
