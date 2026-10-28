# Animal Welfare Hub Köln

The website for the Animal Welfare Hub: coworking in Cologne for people who are seriously committed to food system change, full-time or part-time.

Plain static HTML, no build step. `index.html` is the page, `impressum.html` and `datenschutz.html` are the legal pages.

## Before linking the page anywhere

1. **Impressum address.** `impressum.html` shows only name and city for now. A full address (a c/o address works, a Postfach does not) gets added once there is one to use, for example the hub's own rooms.

## Sign-ups

The form posts to Formspree (`FORM_ENDPOINT` near the bottom of `index.html`), which forwards each sign-up by email.

## Hosting

GitHub Pages, from the `main` branch, root folder: Settings → Pages → Deploy from a branch.
