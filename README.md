# Thiri

Website and rate card for Thiri, a small family design and technology studio.

| File | What it is |
|---|---|
| `index.html` | The website: one self-contained page with no build step. Open it in a browser. |
| `rate-card.pdf` | Client-facing rate card, linked from the site footer |
| `rate-card.html` | Source for the rate card PDF |

## Regenerating the rate card PDF

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --no-pdf-header-footer --virtual-time-budget=8000 --print-to-pdf=rate-card.pdf "file://$PWD/rate-card.html"
```

## Still to fill in

- Contact email and WhatsApp number (currently placeholders)
- Tincy's role description and skills in the team section
- Artist portfolio link
