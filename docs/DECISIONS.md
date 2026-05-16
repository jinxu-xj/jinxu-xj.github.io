# Decisions

Record durable product, architecture, and workflow decisions here.

## 2026-05-14 - Use AcademicPages On GitHub Pages

Context: The user wanted a standard long-term scholar homepage similar to common academic personal sites, not a custom portfolio page.

Decision: Use the AcademicPages template in the `jinxu-xj/jinxu-xj.github.io` repository and publish through GitHub Pages.

Consequences: Future content is maintained through Jekyll Markdown/YAML files. The site has a conventional academic structure and can later support a custom domain.

## 2026-05-14 - Hide Search Indexing During Drafting

Context: The user did not want the unfinished homepage discoverable through search engines.

Decision: Add a site-wide `noindex, nofollow, noarchive, nosnippet` meta tag in `_includes/head/custom.html`; add `robots.txt` explaining that noindex is page-level.

Consequences: Search engines should not index the site, but the direct URL remains accessible. Remove the meta tag when the site is ready to be public/searchable.

## 2026-05-14 - Keep Private Referee Information Off The Website

Context: The original PhD application CV contained referee details.

Decision: Do not publish the original CV or referee information. Add only a placeholder on the CV page until a public CV PDF is available.

Consequences: A scrubbed public CV should be created before linking any PDF from `files/`.

## 2026-05-16 - Add Project Memory Files

Context: The user requested `$pm-init-project` and `$pm-save-memory` to support cross-chat continuity.

Decision: Add `AGENTS.md` and the `docs/` memory files inside the actual website repository, not the outer `Personal Website` container directory.

Consequences: Future Codex sessions can resume by reading `docs/HANDOFF.md`, `docs/PROJECT_MEMORY.md`, `docs/DECISIONS.md`, and `docs/ENV_SETUP.md`.
