# Jiacheng Yao — Personal Website

English academic homepage: https://wearebes.github.io/

The static website lives in `dist/`. Edit `dist/index.html` and `dist/styles.css` to update the page. The public CV is `dist/files/Jiacheng_Yao_CV.pdf`; it excludes grades, examination scores, and the private phone number.

Pushes to `main` deploy `dist/` to GitHub Pages through `.github/workflows/pages.yml`.

For local preview:

```sh
python3 -m http.server 4173 --directory dist
```
