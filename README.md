# Yuk San Chen — homepage

This folder contains the complete static student profile. Study and experience details are summarized from the CV; project descriptions are based on public GitHub repositories. The portrait is the original photo provided by Yuk San Chen, framed as a headshot using CSS. Open `index.html` directly for a quick preview, or serve it locally from the repository root:

```sh
python -m http.server 8000 --bind 127.0.0.1 --directory site
```

Then visit <http://127.0.0.1:8000/>. The page uses only local HTML, CSS and SVG files and also works under a GitHub Pages project path.

## Publish with GitHub Pages

For the user site at <https://theruabit.github.io/>, create or use the public repository named `TheRuabit.github.io` and upload only these six files from this `site/` folder to the repository root: `index.html`, `styles.css`, `favicon.svg`, `.nojekyll`, `README.md`, and `portrait.jpg`. In the repository, open **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then select `main` and `/(root)`. GitHub Pages will publish the site at <https://theruabit.github.io/>. The same files also work in another public repository, at <https://theruabit.github.io/REPOSITORY/>.

Do not upload the enclosing `HomePage` folder or its CV/source documents. See [GitHub’s Pages setup guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).
