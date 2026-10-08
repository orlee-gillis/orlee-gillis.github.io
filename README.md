# Orlee Gillis | Portfolio

Source for the portfolio homepage at <https://orlee-gillis.github.io/>.

The page introduces me as a Senior Technical Writer and points to **Ridgeline**, a fictional security product I documented end to end to show how I build, review and ship documentation.

## What's in this repo

- `index.html` is the whole homepage: one static file with its CSS inline and no build step. The only external request is Google Fonts (Bricolage Grotesque, IBM Plex Sans and IBM Plex Mono).
- `images/` and `styles/` are left over from the previous placeholder page. The current homepage does not use them.

## Related projects

- Ridgeline documentation site: <https://orlee-gillis.github.io/ridgeline-docs/>
- Ridgeline source (Markdown, pull requests, deploy workflow): <https://github.com/orlee-gillis/ridgeline-docs>

## Preview locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000/>.

## Publishing

This is a GitHub Pages user site. Open a pull request against `master`; once it is merged, the page is published at <https://orlee-gillis.github.io/>.
