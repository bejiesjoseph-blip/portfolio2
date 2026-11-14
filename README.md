# Portfolio — Bejies Joseph

Static site: `index.html` + `resume.pdf`. No build step, no dependencies.

## Run locally

    python -m http.server 8000      # then open http://localhost:8000

## Deploy (free)

- **GitHub Pages** — push to the repo, then Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
- **Netlify / Cloudflare Pages** — drag this folder into the dashboard, or connect the repo with no build command and `/` as the publish directory.

## Update content

Edit the matching `<section>` in `index.html`. Replace `resume.pdf` to update the download
(the current file contains a phone number; export a copy without it if you'd rather not publish it).
Add real repo links where the "More on GitHub" link is once you have them.

## Structure

    index.html    # whole site: markup, CSS and JS inline
    resume.pdf    # served by the "Download resume" button
