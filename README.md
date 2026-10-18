# learn.local2598.org

Member guides and explainers from IAFF Local 2598, published with GitHub Pages.

## Layout

- `index.html` is the hub page that lists every guide.
- Each project lives in its own folder with an `index.html`, for example `retirement/`.
- `assets/` holds the shared seal and photos.
- `CNAME` tells GitHub Pages to serve the site at learn.local2598.org. Do not delete it.
- `404.html` is shown for any address that does not exist.

## Adding a new project

1. Create a folder with a short lowercase name, such as `local-101`.
2. Put the project's single HTML file inside it, named `index.html`.
3. Add a card for it in the hub `index.html`.

## Updating a project

Replace that folder's `index.html` and commit. The site updates within a few minutes. Every past version is kept in the commit history and can be restored.

## Before launch

Every page carries `<meta name="robots" content="noindex, nofollow">` so search engines do not list it. Remove that line from each page when the Local is ready to promote the site.

## Rules

- This repository is public. Never add member data, internal documents or anything private.
- Keep two officers as owners of the local2598 organization, with two-step login turned on.
