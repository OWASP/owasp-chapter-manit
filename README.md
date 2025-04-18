# OWASP MANIT Chapter Website

This repository hosts the website for the OWASP Chapter at Maulana Azad National Institute of Technology (MANIT), Bhopal. The site is built using Jekyll and hosted on GitHub Pages, following the style of other OWASP chapter websites like OWASP Chennai.

## Getting Started

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler (`gem install bundler`)
- Jekyll (`gem install jekyll`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/OWASP/owasp-chapter-manit.git
   cd owasp-chapter-manit
   ```

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Run the Jekyll server locally:

   ```bash
   jekyll serve
   ```

4. Open `http://localhost:4000/owasp-chapter-manit` in your browser to preview the site.

### Deployment

- The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.
- Ensure GitHub Pages is enabled in the repository settings (Settings &gt; Pages &gt; Source: `main` branch, `/docs` folder).

## Directory Structure

- `docs/`: Contains all website content and assets.
  - `assets/css/`: CSS styles.
  - `assets/images/`: Images, including the OWASP logo.
  - `_layouts/`: Jekyll layout templates.
  - `*.md`: Markdown files for each page (e.g., `index.md`, `info.md`).
- `_config.yml`: Jekyll configuration file.
- `Gemfile`: Ruby dependencies for Jekyll.
- `README.md`: This file.

## Updating Content

- Edit Markdown files in the `docs/` folder to update content.
- Add new pages by creating `.md` files and updating `_config.yml`’s `header_pages` section.
- Follow OWASP branding guidelines (https://owasp.org/brand/) for logos and colors.

## Contact

- Email: owasp.chap.manit@gmail.com
- LinkedIn: OWASP MANIT Bhopal

## License

Content is licensed under CC-BY-SA 4.0.