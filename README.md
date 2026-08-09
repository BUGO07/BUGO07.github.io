# bugo07.github.io

My personal site. Plain HTML and CSS, no build step, no dependencies.

```
index.html          home — about, education, work, project index
projects/index.html full write-ups for each project
style.css           the whole stylesheet
assets/             favicon
```

## Running locally

Open `index.html` in a browser, or serve the folder if you want the
directory-style links (`projects/`) to resolve exactly like they do in production:

```sh
python3 -m http.server 8000
```

## Deploying

Push to the `main` branch of a repo named `BUGO07.github.io`, then in
**Settings → Pages** set the source to *Deploy from a branch*, branch `main`,
folder `/ (root)`. It goes live at <https://bugo07.github.io>.

The `.nojekyll` file tells GitHub Pages to serve the files as-is instead of
running them through Jekyll.
