# Sprout for Change website

A dependency-free static website for Sprout for Change (S4C). It is ready to publish directly with GitHub Pages—no server, database or build step is required.

## Pages

- `index.html` — Home
- `about.html` — About
- `work.html` — Our Work
- `team.html` — Team
- `get-involved.html` — Get Involved
- `contact.html` — Contact
- `404.html` — GitHub Pages fallback

Shared styles are in `styles.css`, and the mobile menu, restrained reveals and static contact flow are in `script.js`.

## Publish with GitHub Pages

1. Push this folder to the root of a GitHub repository.
2. Open the repository’s **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you publish from (normally `main`) and the `/ (root)` folder.
5. Save. GitHub will provide the public URL after the first deployment.

All links and assets use relative paths, so the site works at both a user-domain root and a project URL such as `username.github.io/sprout-for-change/`.

## Content notes

- Organisation details, contacts and the team roster come from the supplied S4C materials.
- Future or example activities are labelled carefully so they are not presented as completed projects.
- Lorem ipsum appears only in clearly marked, optional future-content areas.
- The three documentary images in `assets/images/` are local, replaceable generated placeholders. Keep the filenames to swap in real S4C photography without changing the HTML.
- The contact form is GitHub Pages-safe: it prepares a message in the visitor’s email app and does not collect or store data.

## Design reference

The approved homepage implementation reference is stored in `design/concepts/` for future visual maintenance.
