# Project Agent Instructions

## Startup

At the start of a new Codex chat in this project:

1. Read `docs/HANDOFF.md`.
2. Read `docs/PROJECT_MEMORY.md`.
3. Read `docs/DECISIONS.md`.
4. Read `docs/ENV_SETUP.md` if setup, commands, or deployment matter.
5. Run Git status before editing.

## Project Context

- This is Jin Xu's AcademicPages/GitHub Pages academic homepage.
- Repository: `jinxu-xj/jinxu-xj.github.io`
- Live URL: `https://jinxu-xj.github.io/`
- Local repository root: `C:\BaiduSyncdisk\codex\Personal Website\github-site\jinxu-xj.github.io`
- The site is currently intentionally hidden from search engines with a `noindex` meta tag while content is being drafted.

## Working Rules

- Preserve user changes. Do not revert files unless explicitly asked.
- Keep durable project context in `docs/PROJECT_MEMORY.md`.
- Keep current task state in `docs/HANDOFF.md`.
- Record important decisions in `docs/DECISIONS.md`.
- Keep secrets and private referee information out of tracked files.
- Do not publish a CV PDF until it has been scrubbed of referee/private information.

## Common Maintenance Targets

- `_config.yml`: sidebar identity, email, ORCID, Google Scholar, GitHub, SSRN, site metadata.
- `_pages/about.md`: homepage bio, interests, selected research, news.
- `_pages/publications.html`: research page shell.
- `_publications/`: one Markdown file per paper.
- `_pages/teaching.html`: teaching and academic service.
- `_pages/cv.md`: public CV-style content and CV PDF link.
- `_includes/head/custom.html`: current `noindex` setting.
- `files/`: public CV and paper PDFs.
- `images/profile.png`: currently not displayed; only use if the user later asks to add a formal portrait.

## Before Ending A Work Session

Update `docs/HANDOFF.md` when useful, especially before switching computers, changing branches, publishing, or pausing a multi-step homepage revision.
