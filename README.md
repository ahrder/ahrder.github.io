# Andrew Harder — Academic Pages

This is Andrew Harder's website using the actual [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template. It uses the template's built-in **contrast** palette and standard profile sidebar, navigation, layouts, and theme switcher. No custom redesign or imitation theme is used.

## Edit content

- `_pages/about.md` — home page biography
- `_pages/research.md` — overview, preprints, publications, notes, slides, and supervision
- `_pages/teaching.md` — courses and teaching history
- `_pages/other.md` — seminars and conferences
- `_config.yml` — name, sidebar biography, affiliation, portrait, theme, and site address
- `_data/navigation.yml` — top navigation
- `images/andrew-harder.jpg` — original portrait

The publication list is kept in a single Markdown page to preserve the source's ordering, statuses, and years without inventing exact publication dates. All 40 external content links are retained. The Google Drive notes/slides remain links to the existing files.

## Publish to GitHub Pages

Repository: <https://github.com/ahrder/ahrder.github.io>. Website address: <https://ahrder.github.io>.

Edit the source on `main`. The included workflow builds the site and publishes the generated HTML to `gh-pages`, matching the repository's existing deployment arrangement. In **Settings → Pages**, the publishing source should remain **Deploy from a branch → gh-pages → / (root)**. The `gh-pages` branch contains generated output and should not be edited manually.

Pull requests build for validation without deploying. Deployment commits preserve the previous `gh-pages` history. The earlier al-folio source remains recoverable from the `main` history.

## Preview locally

Requires Ruby 3.3 and Bundler:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

Open <http://127.0.0.1:4000>. The theme's sun/moon button switches between its built-in light and dark modes. The initial mode follows the visitor's system preference.

## Provenance

- Source content: <https://sites.google.com/view/anh318>, retrieved October 19, 2026.
- Theme source: Academic Pages commit `7b958332ce9970cfb6987a049d7684ac615397e8`.
- Upstream documentation is preserved in `UPSTREAM.md`, and the MIT license in `LICENSE`.
- Sample publications, teaching, blog posts, portfolio items, talks, and personal profile links have been removed from the new site.
- The original Google Site has not been changed.
- Teaching still begins with Spring 2025, as in the source. Publication statuses are also preserved. No email address was supplied in the public source content, so none was inferred.

This Academic Pages folder supersedes the earlier custom HTML draft in `andrew-harder-website`.
