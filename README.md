# Tim Reardon — portfolio site

A single-file portfolio page (`index.html`) built for GitHub Pages. No build step, no frameworks.

## Publish it

1. Create a public repo named `treardontech.github.io` .
2. Put `index.html` and this `README.md` in the root of the repo.
3. Keep `tim-reardon.jpg` (the headshot) in the same folder, and add your CV as `cv.pdf` so the "Download CV" button works.
4. Push. Then open the repo's Settings > Pages and set the source to the `main` branch, root folder.
5. After a minute or two the site is live at `https://treardontech.github.io`.

## Edit it

Everything is in `index.html`, with comments marking the parts worth changing:

- Colors and fonts: the `:root` block at the top of the `<style>` section.
- Projects: the `<section id="projects">` block. Each project is one `<li>`. Add a repo link inside the `<h3>` when a project has a public repository.
- Timeline: the `<section id="timeline">` block. Each entry is a `tl-year` cell plus a `tl-item`, sharing a `grid-row` number. Use `class="tl-item left"` for clinical roles and `right` for study, data, and teaching.
- Contact: the `<section id="contact">` block.
