# debuggerrr.github.io

Simple GitHub Pages portfolio for Sid. This repository contains a lightweight single-page portfolio you can customize and publish with GitHub Pages.

Files:
- `index.html` — main page
- `styles.css` — styles

Publish:
1. Commit and push to the `main` branch.
2. In your GitHub repo settings -> Pages, set the source to the `main` branch (root) and save.
3. Visit `https://debuggerrr.github.io` after a minute.

Note about Jekyll:
- I briefly added a Jekyll scaffold, but removed it to keep the repository as a simple static site. The static `index.html` is the current homepage, so GitHub Pages will serve it directly.
- To show your avatar on the static homepage, keep your photo at the repository root named `sid.png` (you already copied it). The static `index.html` references `sid.png`.
 - To show your avatar on the static homepage, keep your photo at the repository root named `sid.png` (you already copied it). The static `index.html` references `sid.png`.
 - To show certification logos, add two files to the repo root named `aws_data_analytics.png` and `snowpro_core.png`. They will appear in the "Certifications" section automatically. If you prefer SVGs, use `.svg` instead and update the filenames in the markup.
- I added inline SVG badge fallbacks for AWS Data Analytics and SnowPro Core so the Certifications section shows even if logo files are not uploaded. To use official logos, add `aws_data_analytics.png` and `snowpro_core.png` to the repo root and the PNGs will display instead of the SVG badges.
 - Avatar behavior: the site now uses your GitHub profile avatar as the primary image (so a headshot always displays). If you'd prefer to use a custom avatar, replace the repository root `sid.png` with a square headshot and it will be used as a fallback.

Customize:
- Replace text in `index.html` (name, bio, projects).
- Add your project links, images, or embed demos.
- For a blog or advanced features, consider using Jekyll, Hugo, or a static-site generator.
# debuggerrr.github.io