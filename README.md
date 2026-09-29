# Corruption Compass

A pixel-arcade game of ten bribery offers. Name your price for each one, from
"for free" to "never", and land on a two-axis compass: how far you would go,
and how cheaply.

Plain HTML, no build step. Open `index.html` or deploy the folder as a static site.

## Data collection

When a game finishes on the public site, the page posts one entry to a Netlify
form named `results` with the position (`x`, `y`), the result `type`, how many
offers were `taken`, the money `total`, and the ten answers `q1` to `q10`.
No name or contact detail is sent. Form detection must be enabled in the
Netlify site settings for the form to be registered at build time.
