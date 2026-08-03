# Jiazheng Li - Personal Academic Homepage

Personal academic homepage for Jiazheng Li, built with [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll).

**Live site:** https://jiazhenglithu.github.io

## Project Structure

```
├── _config.yml          # Site configuration
├── _data/               # Navigation and UI text data
├── _includes/           # Reusable HTML partials (header, footer, author profile, etc.)
├── _layouts/            # Page layout templates
├── _pages/              # Site pages (about, publications, 404)
├── _publications/       # Publication entries
├── _sass/               # SCSS stylesheets
├── assets/              # CSS, JS, fonts
├── files/               # Downloadable files (CV PDF)
├── images/              # Avatar and favicon images
├── Gemfile              # Ruby dependencies
└── package.json         # Node.js dependencies (for JS build)
```

## Local Development

```bash
# Install dependencies
bundle install

# Start dev server (auto-reload on changes)
bundle exec jekyll serve -l -H localhost

# Rebuild frontend JS (only if modifying JS source)
npm run build:js
```

Note: changes to `_config.yml` require restarting the server.

## Deployment

Automatically built and deployed via GitHub Pages on push to the main branch.
