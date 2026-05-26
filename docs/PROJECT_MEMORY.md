# Project Memory

## Snapshot

- Project: Jin Xu academic homepage.
- Purpose: Long-term academic personal website for empirical corporate finance / empirical asset pricing.
- Primary user: Jin Xu.
- Public URL: `https://jinxu-xj.github.io/`.
- GitHub repository: `jinxu-xj/jinxu-xj.github.io`.
- Current stage: Draft AcademicPages site; intentionally kept out of search engine results while content is revised.

## Architecture

- App/framework: AcademicPages Jekyll site for GitHub Pages.
- Branch: `master`.
- Important modules:
  - `_config.yml` for site metadata and sidebar identity.
  - `_data/navigation.yml` for top navigation.
  - `_pages/` for Home/About, Research, Teaching, CV pages.
  - `_publications/` for one Markdown file per paper.
  - `_includes/head/custom.html` for custom head tags including temporary search hiding.
  - `images/profile.png` exists but the sidebar avatar is currently disabled.
  - `files/` for public CV and paper PDFs.
- External services: GitHub Pages; future ORCID, Google Scholar, SSRN/RePEc links may be added.

## Local Conventions

- Git command: use GitHub Desktop bundled git if `git` is not on PATH:
  `C:\Users\12428\AppData\Local\GitHubDesktop\app-3.5.8\resources\app\git\cmd\git.exe`
- Dev command if Ruby/Jekyll is installed: `bundle exec jekyll serve -l -H localhost`.
- GitHub Pages deployment happens after pushing to `master`.
- Keep website content edits concise and academic; prefer standard scholar homepage style over portfolio/marketing styling.

## Important Paths

- Repository root: `C:\BaiduSyncdisk\codex\Personal Website\github-site\jinxu-xj.github.io`
- Home page content: `_pages/about.md`
- Research page shell: `_pages/publications.html`
- Publication entries: `_publications/`
- Teaching/service page: `_pages/teaching.html`
- CV page: `_pages/cv.md`
- Search hiding: `_includes/head/custom.html`
- Maintenance notes: `JINXU_SITE_NOTES.md`

## Durable Context

- The repository was created from the AcademicPages template.
- Template example posts, talks, teaching entries, portfolio pages, and sample PDFs were removed during customization.
- Current navigation is `Research`, `Teaching`, `CV`; the root page is the About/Home page.
- Current sidebar identity:
  - Name: Jin Xu
  - Bio: Empirical Corporate Finance | Empirical Asset Pricing
  - Location: Hong Kong
  - Employer: The Chinese University of Hong Kong
  - Email: `jinxu0209@gmail.com`
- No Website, GitHub, or avatar is displayed in the sidebar.
- ORCID, Google Scholar, SSRN/RePEc links are not yet filled in.
- A public CV PDF has not been added yet because the original CV includes private referee information.
- The CV page is intentionally empty until a public CV link/PDF is added.
- Teaching page intentionally keeps only the TA entry.
- The footer intentionally keeps only the site last-updated date.
- The theme toggle is intentionally hidden.
- Published paper currently listed:
  - Xiaoran Ni, Jin Xu, and David Yin. "Are Enhanced Creditor Rights in Bankruptcy Desirable to Shareholders? Evidence from the Cost of Equity Capital." Journal of Banking & Finance, Volume 175, 2025, Article 107442. DOI: `10.1016/j.jbankfin.2025.107442`.
- Working papers currently listed:
  - "CEO Rugged Individualism and Workplace Safety"
  - "Classified Board and Workplace Safety"

## Watchouts

- The live site is accessible by direct URL even with `noindex`; `noindex` only discourages search engine indexing.
- To make the site inaccessible, disable GitHub Pages or change repository/pages visibility settings on GitHub.
- Do not publish referee contact details or private CV content.
- Mainland China access to `github.io` may be unstable; consider a future custom domain or mirror if China-facing access becomes important.
