# bgally.github.io

The public GitHub Pages site (https://bgally.github.io/), repo `BGally/BGally.github.io`, branch `main`, served from the root. It holds only built pages; their sources live in private repos.

- **This repo is public. Commits must use the GitHub noreply address**, set in this repo's local git config (`user.email` = `10654898+BGally@users.noreply.github.com`). Never commit with the personal email, and keep secrets and private material out.
- `plasmodia/index.html` is the built Plasmodia page. Don't edit it here: in `projects/plasmodia` run `npm run publish`, which builds, copies it in, commits and pushes. `plasmodia/plasmodia.html` forwards the page's first address (live for a few minutes on 2026-10-23) to the current one.
- `index.html` is a plain landing page that links to each project.
- `.nojekyll` makes Pages serve the files as they are.
