# Website
Create a website about myself and my lab and update it from time to time

## Site structure

- `index.html`, `research.html`, `publication.html`, `lab.html`, `news.html`: the main pages (plain HTML; edit them directly).
- `style/`: page styles.
- `images/`: profile photo and favicon.

## Publishing

The site is built with Jekyll and deployed by `.github/workflows/deploy-pages.yml` on every push to `main`.
GitHub Pages must be enabled once by a repository admin: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
The site is then served at <https://jpchampati.github.io/Website/>.

The layout is based on [research-lab-website](https://github.com/ericdaat/research-lab-website) (MIT License).
