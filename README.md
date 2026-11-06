# Bill DeRose's personal website

Live site: https://wderose.github.io/

A responsive, dependency-free personal website, updated from Bill's November 2026 résumé. This repository was forked from `bderose/website` to preserve its history, then migrated from Hugo/Travis to static HTML and CSS. The old Hugo sources and photographs remain available in Git history.

## Editing

- `index.html`: biography, experience, research, education, and contact links.
- `resume.html`: complete, print-friendly résumé.
- `resume.md`: downloadable text résumé.
- `styles.css`: responsive screen and print styles.
- `assets/`: portrait and favicon.
- `sitemap.xml`: canonical URLs and update dates.

Keep résumé dates, qualifications such as “estimated” and “projected,” and patent application versus granted-patent status accurate when editing. The homepage deliberately summarizes experience; the résumé retains the full detail. No JavaScript, package installation, or build step is required.

## Preview

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000/. The résumé can be printed or saved as PDF using the browser's Print command.

## GitHub Pages

In **Settings → Pages**, select **Deploy from a branch**, choose **master** and **/(root)**, then save. `.nojekyll` publishes the files directly. Pushes to `master` update the site automatically.

The repository must be named `wderose.github.io` to serve the account's root URL. The former `bderose` repositories and website are separate and have not been modified. A redirect at the old URL requires access to the separate `bderose/bderose.github.io` repository.
