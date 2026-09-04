# Scriptly

Scriptly is a personal writing & communication service. Customers submit what they need written — emails, letters, resumes, speeches, essays, and other personal or professional messages — and receive a personalized draft back, with revisions included.

This repository holds the public website: the landing page, pricing, and legal documents.

## Live site

[Add your live URL here once deployed, e.g. `https://yourusername.github.io/scriptly-website/`]

## Template / file structure

This is a static, single-page site — no build step or framework required.

```
scriptly-website/
├── index.html                     # Full site: hero, how-it-works, request form, pricing, legal
├── Scriptly_Terms_of_Use.docx     # Terms of Use (Word format, downloadable from the site)
├── Scriptly_Privacy_Policy.docx   # Privacy Policy (Word format, downloadable from the site)
├── README.md
└── LICENSE
```

`index.html` is self-contained — all styles and scripts are inline, with fonts loaded from Google Fonts. No dependencies to install.

## Pricing (as of this version)

| Plan | Monthly | Annual (10% off) | Includes |
|---|---|---|---|
| Free | $0 | $0 | 1 piece / month |
| Basic | $1 | $10.80/yr | 10 pieces / month |
| Plus | $2.99 | $32.29/yr | 16 pieces / month |
| Unlimited | $9 | $97.20/yr | Unlimited pieces, priority turnaround |

Prices are shown in USD; an approximate Ghana cedi (GHS) equivalent is shown alongside for convenience.

## Legal

The Terms of Use and Privacy Policy are embedded directly on the site (see the Legal section) and are also available as standalone `.docx` files in this repo. Both documents still need an effective date and contact email filled in before the site goes live — search for `[Insert Date]` and `[Insert Contact Email]` in the docs.

## Status

This is currently a front-end prototype. The request form on the site is a visual mock and is not yet connected to a backend or an AI drafting engine.

## License

See [LICENSE](./LICENSE). All rights reserved — this is proprietary business code, not open source.
