# TheOnlineDarkAngel

Dark Angel is a single-page campaign site for Ashley Woods' limited sneaker release with AliveShoes.

The page presents both shoe silhouettes, explains the reservation process, and links visitors to the official AliveShoes product pages for sizing, checkout, and payment.

## Live site

This project is configured for deployment with GitHub Pages through [`.github/workflows/deploy-pages.yml`](./.github/workflows/deploy-pages.yml).

After the repository is pushed to GitHub:

1. Open **Settings → Pages**.
2. Set the source to **GitHub Actions**.
3. Pushes to `main` will deploy the site automatically.

## Local preview

No build tools or dependencies are required. Open [`index.html`](./index.html) directly in a browser, or serve the folder with any static file server:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project structure

```text
.
├── .github/
│   └── workflows/
│       └── deploy-pages.yml
├── .nojekyll
├── index.html
└── README.md
```

## Technology

- Semantic HTML
- Inline CSS
- Inline image assets
- Google Fonts: Bodoni Moda and Work Sans
- GitHub Pages with GitHub Actions

## External links

Reservations and checkout are handled by AliveShoes:

- [Online Dark Angel](https://www.aliveshoes.com/online-dark-angel-1)
- [OnlineDarkAngel](https://www.aliveshoes.com/onlinedarkangel)
