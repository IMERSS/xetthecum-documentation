# Xetthecum Ecocultural Mapping: A Learning Journey

Documenting the story behind the Xetthecum Digital Ecocultural Mapping project and its outcomes.

This repository holds the source for the project's documentation site, browsable on the
[GitHub Pages site](https://imerss.github.io/xetthecum-documentation) for this repository. It mirrors the structure of
[IMERSS/detecting-local-extinction](https://github.com/IMERSS/detecting-local-extinction): a
[Hugo](https://gohugo.io/) site using the [Hextra](https://github.com/imfing/hextra) theme, which can also be
built from R with [blogdown](https://github.com/rstudio/blogdown).

## Building the site

The site is built with Hugo **0.121.0 (extended)** and published from the `docs/` directory.

From R:

```r
blogdown::build_site()
```

Or directly with Hugo:

```bash
hugo
```

To preview locally, use `blogdown::serve_site()` or `hugo server`.

## Structure

* `content/docs/` – the documentation, one folder per section:
  `overview`, `phase-i`, `phase-ii`, `phase-iii`, `conclusion` and `references`
* `content/_index.md` – the landing page (cover image: `content/featured-background.jpg`)
* `layouts/`, `assets/`, `static/` – IMERSS customizations of the Hextra theme, shared with other IMERSS documentation sites
* `themes/hextra` – vendored copy of the Hextra theme

The content was adapted from the project report *Xetthecum Ecocultural Mapping Project*, version 3.0 (1 May 2024).
