# Jeewan's Homepage

Personal website of Jeewan Gamage, built with [Quarto](https://quarto.org) and published with GitHub Pages at https://jeewangamage.github.io.

## Editing the site (no software needed)

1. On any page of the live site, click **Edit this page** (left-hand side, under the page contents). GitHub opens that page's source.
2. Make your change in the editor (it is plain text with Markdown formatting), then click **Commit changes**.
3. Within about two minutes the "Publish website" action rebuilds the site and your change is live.

To add an image or PDF: in this repository open the `images/` folder, click **Add file, Upload files**, then reference it from a page, for example `![caption](images/myphoto.jpg)`.

## Pages

| File | Page |
|---|---|
| `01-index.qmd` | Home |
| `02-career.qmd` | Career |
| `03-publications.qmd` | Publications |
| `04-digital.qmd` | Digital Resources |
| `05-talks.qmd` | Talks |
| `06-contact.qmd` | Contact |
| `_quarto.yml` | Site settings: navigation, colours, footer, social links |
| `styles.css` | Extra styling |

## Editing on your computer (optional)

Install [Quarto](https://quarto.org/docs/get-started/) (and RStudio if you like), open the folder, and run `quarto preview` to see changes live. Push to `main` to publish.

## Photos to replace

- Headshot: upload a square photo as `images/me.jpg`, then in `01-index.qmd` change `images/me.svg` to `images/me.jpg`.
- Field photo: upload `images/field.jpg`, then in `01-index.qmd` change `images/field.svg` to `images/field.jpg`.

## Publishing settings (already done once)

The site is built and deployed by `.github/workflows/publish.yml`
(Settings, Pages, Source: GitHub Actions). The earlier hand-built page is kept in `legacy/`.
