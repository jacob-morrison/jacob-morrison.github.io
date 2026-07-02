# jacobmorrison.com

Personal website of Jacob Morrison. Custom lightweight Jekyll site (no theme).

## Develop

```
bundle install
bundle exec jekyll serve   # http://127.0.0.1:4000/
```

## Where content lives

- Homepage prose and section layout: `_layouts/home.html`
- Publications (home + /publications): `_data/publications.yml`
- Talks, press & testimony: `_data/talks.yml`
- Sidebar (affiliations, socials, CV link): `_includes/site_sidebar.html`
- Styles: `assets/css/site.scss`

Deploys to GitHub Pages from `master` via `.github/workflows/pages.yml`.
