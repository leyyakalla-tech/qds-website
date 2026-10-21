# QDS website

The website of Quintessence Development Solutions (QDS), at qdsbusiness.com.

It's a plain static site: HTML and one stylesheet, with no build step and nothing to update or patch. It's hosted free on GitHub Pages from the `main` branch.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The homepage (all sections) |
| `privacy.html` | Privacy policy (POPIA) |
| `404.html` | Shown for old WordPress links that no longer exist |
| `styles.css` | All styling. Brand colours are at the top. |
| `assets/` | Logo, emblem, favicon and social-share image |

## Editing

To edit text, open `index.html` on GitHub, click the pencil icon, change the words and commit. The live site updates within about a minute.

## Brand

The colours and type follow the *QDS Design & Brand Guidelines v2.0 (January 2021)*:
- logo green `#006838`
- royal blue `#2B3990`
- turquoise `#27AAE1`
- dark grey `#565454`, plus the pastel set

The guideline specifies Calibri for the web. Carlito, which has the same metrics, is loaded as the fallback. Turquoise text on white uses a darker step, `#187AA8`, so it stays legible.

## Custom domain (qdsbusiness.com)

1. Ask the domain provider to set these DNS records, and to leave the MX (email) records unchanged:
   - `A` records for `qdsbusiness.com`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`
   - a `CNAME` record for `www`: `leyyakalla-tech.github.io`
2. Once the records resolve, go to the repo's **Settings → Pages → Custom domain**, enter `qdsbusiness.com`, then tick **Enforce HTTPS**.

## Still to add

- A portrait photo: put it at `assets/leyya-kalla.jpg` and swap it in where `index.html` says "Replace with a portrait".
- Insights articles (later, from LinkedIn).
