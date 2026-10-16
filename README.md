# neenerrh.github.io

Personal academic website of **Hafsa Kabir Ahmad, PhD**, Senior Lecturer and Faculty Deputy Dean, Faculty of Computing, Bayero University Kano.

Built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and adapted from [isahmadbbr.github.io](https://isahmadbbr.github.io/).

## Where to edit

| What | File |
| --- | --- |
| Name, site description, URL | `_config.yml` |
| Home page bio and links | `_pages/about.md` |
| Profile photo | add `assets/img/prof_pic.jpg`, then uncomment `image:` in `_pages/about.md` |
| Publications | `_bibliography/papers.bib` (`selected={true}` shows a paper on the home page) |
| CV page | `_data/cv.yml`; downloadable PDF is `assets/pdf/hafsa_cv.pdf` |
| Teaching page | `_pages/teaching.md` |
| News | `_news/*.md` |
| Social links | `_data/socials.yml` |

## Deploy

1. Create a public GitHub repository named `neenerrh.github.io`.
2. Push this folder to its `main` branch.
3. In the repository's **Settings → Actions → General**, give workflows read and write permissions.
4. Wait for the **Deploy site** action to finish. It builds the site into the `gh-pages` branch.
5. In **Settings → Pages**, set the source to the `gh-pages` branch.

The site is then live at <https://neenerrh.github.io>.

## Local preview

```bash
docker compose pull && docker compose up
```

Then open <http://localhost:8080>.
