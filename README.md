# Animal Welfare Hub Köln

The website for the Animal Welfare Hub: coworking in Cologne for people who work full-time on animal welfare or firmly plan to.

Plain static HTML, no build step. `index.html` is the page, `impressum.html` and `datenschutz.html` are the legal pages.

## Before linking the page anywhere

1. **Fill in the Impressum.** Replace the bracketed placeholders in `impressum.html` with an address where post reaches you (a c/o address works, a Postfach does not).

## Sign-ups

The form posts to Formspree (`FORM_ENDPOINT` near the bottom of `index.html`), which forwards each sign-up by email.

## Hosting

GitHub Pages, from the `main` branch, root folder: Settings → Pages → Deploy from a branch.
