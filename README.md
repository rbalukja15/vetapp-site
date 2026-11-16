# vetapp-site

Public marketing site for VetApp, clinic management software for veterinarians.

A single static page (`index.html`) in English and Albanian, with no build step.
The language switch lives in the page script: English text is in the HTML, the
Albanian strings are in the `SQ` object. Change both when you change copy.

## Preview locally

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Hosting

Meant for Cloudflare Pages: connect this repo, no build command, output
directory `/`. `_headers` sets the security headers there.

## Rules

- No real clinic data or the current clinic's name, in copy or screenshots.
- Placeholders still to fill: contact email, phone, price.
