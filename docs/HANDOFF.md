# Handoff

Last updated: 2026-05-26

## Current Progress

- Project root: `C:\BaiduSyncdisk\codex\Personal Website\github-site\jinxu-xj.github.io`.
- Remote repository: `https://github.com/jinxu-xj/jinxu-xj.github.io`.
- Live URL: `https://jinxu-xj.github.io/`.
- Site framework: AcademicPages/Jekyll on GitHub Pages.
- Current branch: `master`.
- Site is live but intentionally hidden from search engine indexing with `noindex, nofollow, noarchive, nosnippet` in `_includes/head/custom.html`.
- `robots.txt` exists and notes that search hiding is handled by page-level noindex.
- Current local Git state before this checkpoint: clean and in sync with `origin/master`.
- Current requested cleanup removes visible Website/GitHub links, theme toggle, extra footer links, CV text, and non-TA teaching/service items.
- Current identity is first-year PhD student in the School of Accounting and Finance at The Hong Kong Polytechnic University.

## Completed

- AcademicPages template was customized into Jin Xu's academic homepage.
- Template sample pages, sample posts, sample talks, sample teaching entries, portfolio pages, and sample PDFs were removed.
- Navigation is simplified to `Research`, `Teaching`, and `CV`.
- Homepage content lives in `_pages/about.md`.
- Homepage now includes a brief Education section, including the PolyU PhD entry.
- Research entries live in `_publications/`.
- Current listed research includes one published Journal of Banking & Finance article, two working papers, and one inactive research item.
- Teaching page lives in `_pages/teaching.html` and currently shows only the TA entry.
- CV page lives in `_pages/cv.md` and currently has no visible body text until a CV link/PDF is added.
- Sidebar/site metadata is configured in `_config.yml`; Website and GitHub are currently blank/hidden.
- Sidebar avatar is enabled with `images/profile.png`, cropped from `C:\Users\12428\Desktop\XU Jin_edited.png`.
- SSRN profile is set in `_config.yml`.
- Footer is simplified to only the site last-updated date.
- Root working folder was cleaned so `C:\BaiduSyncdisk\codex\Personal Website` only contains `github-site`.
- Project memory files exist: `AGENTS.md`, `docs/PROJECT_MEMORY.md`, `docs/HANDOFF.md`, `docs/DECISIONS.md`, and `docs/ENV_SETUP.md`.

## Next Steps

1. Add real ORCID URL, Google Scholar URL, and any RePEc links to `_config.yml`.
2. Replace or recrop `images/profile.png` if the user wants a different portrait framing.
3. Add a public CV PDF to `files/` only after removing referee/private information, then link it from `_pages/cv.md`.
4. Refine homepage bio, research wording, paper summaries, author order, and news items to match finance/economics academic homepage norms.
5. Decide whether to keep `noindex`, unpublish GitHub Pages temporarily, or replace the live page with a minimal under-construction page.
6. Remove `noindex` only when the user is ready for search engines to index the site.

## Blockers And Risks

- ORCID, Google Scholar, and RePEc links are still missing.
- Public CV PDF is still missing.
- The live site is not indexed but remains accessible to anyone with the direct URL.
- GitHub Pages build status should be checked after future pushes, especially after `_config.yml` or Liquid template changes.
- GitHub may create automated `talkmap` commits; fetch before pushing if remote history changes.
- Mainland China access to `github.io` may be unstable; a custom domain or mirror may be needed later.
