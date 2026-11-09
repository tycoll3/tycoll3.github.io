# Ty Collins — personal site

Plain HTML and CSS. No build step, no packages, no trackers.

## Files

- `index.html` — home page: work, projects, approach, experience, contact
- `projects/` — one case study page per project
- `demos/` — the two Scorigami maps, copied from the Scorigami project's output
- `assets/style.css` — all styling, with light and dark themes
- `assets/og.png` — share image
- `404.html` — missing-page page, in the same style
- `robots.txt`, `sitemap.xml`

## Preview on this PC

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8790
```

Then open http://127.0.0.1:8790

## Publish free with GitHub Pages

1. On github.com, create a new **public** repository named `tycoll3.github.io`.
2. Push this folder to that repository's `main` branch.
3. In the repository, open Settings → Pages and set the source to the `main` branch.
4. The site appears at https://tycoll3.github.io within a few minutes.

## Editing

- To add a project, copy a page in `projects/`, change the text, and add a card to the `#projects` section of `index.html`.
- To refresh a Scorigami demo, rebuild it in the Scorigami project and copy the output file over the one in `demos/`.
- Keep the numbers on the home page the same as the resume.
