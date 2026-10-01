# calgonzalezz.github.io

Personal academic website for Carlos Gonzalez-Regalado.
Built with [Jekyll](https://jekyllrb.com/), hosted on [GitHub Pages](https://pages.github.com/).

Live at: https://calgonzalezz.github.io

## Stack

- Jekyll 4 (custom theme, no external dependencies on AcademicPages or Minimal Mistakes)
- Source Serif Pro + Inter (Google Fonts)
- GoatCounter for privacy-friendly analytics
- Plugins: jekyll-feed, jekyll-seo-tag, jekyll-sitemap

## Structure

```
.
├── _config.yml              # site config, author info, navigation
├── _data/navigation.yml     # main menu
├── _layouts/                # default + page layouts
├── _includes/               # head, header, sidebar, footer
├── _pages/                  # CV, publications, talks, podcasts, 404
├── _sass/                   # (empty, room for partials)
├── assets/css/main.scss     # all styles
├── assets/images/           # avatar, favicon
├── files/                   # PDFs (CV, working papers)
├── index.md                 # home page
├── Gemfile                  # ruby dependencies
└── README.md
```

## Local development

Requires Ruby 3.x and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Site will be available at http://localhost:4000.

## Editing content

- **Home page** → `index.md`
- **CV** → `_pages/cv.md`
- **Publications** → `_pages/publications.md`
- **Talks** → `_pages/talks.md`
- **Podcasts** → `_pages/podcasts.md` (Spotify show embed; new episodes appear automatically)
- **Author info & links** → `_config.yml` under `author_profile`
- **Menu items** → `_data/navigation.yml`
- **Colors / typography** → `assets/css/main.scss` (CSS variables at top)

## Files to upload

- `/files/cgonzalez_CV.pdf` — CV linked from the CV page
- `/assets/images/profile.jpg` — avatar (square, 600×600px or larger)
- `/assets/images/favicon.svg` — browser tab icon

Working-paper PDFs are linked from Dropbox in `_pages/publications.md` and `_pages/cv.md`.

## Analytics

Visits are tracked with GoatCounter at https://cgonzalezr.goatcounter.com (script in `_includes/head.html`).

## License

Site content © Carlos Gonzalez-Regalado. Code structure available under MIT license.
