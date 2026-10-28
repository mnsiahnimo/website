# Michael Nsiah-Nimo — Academic Website (Quarto)

Green (#1F3D30) and beige theme matching the design canvas: Newsreader + IBM Plex fonts,
numbered sections, full-width green band. Pages: About (home), Research, Publications, CV.

## Preview / build (RStudio or terminal)
    quarto preview      # live preview while editing
    quarto render       # builds the site into docs/
After every render, make sure docs/.nojekyll exists (on Mac/Linux: touch docs/.nojekyll).

## Publish to GitHub Pages
Push this folder to your GitHub repo (e.g. mnsiahnimo.github.io), then in GitHub:
Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/docs`.
NOTE: pushing to mnsiahnimo.github.io replaces the site currently there.

## Custom domain (optional)
Add a file named CNAME (no extension) to the project root containing just your domain,
e.g.  michaelnsiahnimo.com , list it under `resources:` in _quarto.yml, re-render, and
set the same domain in Settings → Pages → Custom domain.

## Still to fill in (search the files for "TO BE SUPPLIED")
- Email, LinkedIn and Google Scholar links (index.qmd)
- Exact title and co-authors of the CLHLS manuscript; other publications and presentations (index.qmd, publications.qmd)
- PhD start year; UTEP dates; Data Analyst organization and dates; MS year and institution (index.qmd, cv.qmd)
- One-line focus for each research card (index.qmd, research.qmd)
- All of Us role and dates; other funded projects (research.qmd)
- CV PDF: put it in files/ and update the link in cv.qmd; awards & service

Colors live at the top of green.scss.
