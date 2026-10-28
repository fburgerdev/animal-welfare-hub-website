# Animal Welfare Hub Köln

The website for the Animal Welfare Hub: coworking in Cologne for people who work full-time on animal welfare or firmly plan to.

Plain static HTML, no build step. `index.html` is the page, `impressum.html` and `datenschutz.html` are the legal pages.

## Before linking the page anywhere

1. **Connect the sign-up form.** Create a free form at a form service (for example Formspree), copy its form URL and put it into `FORM_ENDPOINT` near the bottom of `index.html`. Until then the form says it is not connected yet.
2. **Fill in the Impressum.** Replace the bracketed placeholders in `impressum.html` with an address where post reaches you (a c/o address works, a Postfach does not).
3. **Name the form service in the Datenschutz.** Replace the bracketed placeholder in `datenschutz.html` with the service's name and where it is based.

## Hosting

GitHub Pages, from the `main` branch, root folder: Settings → Pages → Deploy from a branch.
