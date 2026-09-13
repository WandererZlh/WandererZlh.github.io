# Lihang Zhou — Academic Website (v2)

This is the second version of my academic website, based in part on the
[A.P Jekyll theme](https://github.com/kssim/ap) by KyeongSeob Sim,
licensed under the MIT License.

The homepage contains my profile, research interests, papers, talks, brief CV,
contact links, and footer artwork. A shared header provides links to the About
page and a blank Portfolio template.

## Editing content

- Personal information, research interests, CV, and external links: `_data/profile.yml`
- Papers: `_data/papers.yml`
- Talks: `_data/talks.yml`
- Homepage structure: `index.html`
- Shared page header and document metadata: `_layouts/default.html`
- Visual styling: `assets/css/site.css`
- Blank Portfolio template: `portfolio/index.html`

Free-form content is written as Markdown in each `body` field, including links
such as `[QMAP](https://qmap.ucdavis.edu/)`. Talk dates are displayed as written,
and talks appear in the same order as `_data/talks.yml`.

Images are stored in `assets/img/`, and downloadable slides are stored in
`assets/pdf/`.

## Local preview

```sh
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Build

```sh
bundle exec jekyll build
```

The generated site is written to `_site/`. Do not edit files in `_site/`
directly because they are regenerated on every build.