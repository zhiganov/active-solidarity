# OSS Audit: active-solidarity

Date: 2026-04-20
Focus: Full audit
Based on: "Producing Open Source Software" by Karl Fogel

## Caveat

This is a content/docs repo, not a software project — ~1 day old, single author, explicitly a personal thinking-space. Fogel's framework targets code projects and many items are genuinely n/a here. `[n/a]` is used generously where applying the item would be performative rather than useful.

## Summary

- Applicable items: 43 / 66
- Present: **13 / 43** (30%)
- Partial: 5
- Missing: 25
- N/A: 23

## 1. Project Identity & Presentation

- [x] **Clear project name** — `active-solidarity`; memorable, searchable, not a pun.
- [~] **Name claimed in key namespaces** — GitHub `zhiganov/active-solidarity` claimed; no domain; npm/PyPI n/a.
- [x] **Mission statement** — README lede frames the premise in ~60 words.
- [x] **Explicit open-source statement** — CC BY-SA 4.0 named in README with link.
- [x] **Development status indicated** — "Early and provisional. A live thinking-space, not a publication." Honest.
- [x] **Features list or overview** — two-track structure (research/concept) described.

## 2. Documentation

- [x] **README with quickstart** — for a thinking repo, the README is the entry; it tells you where to go first.
- [n/a] **Tutorial/example** — docs-only repo; `docs/origin.md` is effectively the worked example.
- [x] **Developer/architecture docs** — monorepo structure explained in README + folder READMEs.
- [n/a] **API documentation** — no API.
- [n/a] **Screenshots/demo/video** — no visual output; landing page *is* the presentation.
- [ ] **CHANGELOG maintained** — none.
- [~] **Documentation gaps acknowledged** — `commitments.md` flags pending principles draft; `research/README.md` flags the missing Utopian book title. Scattered rather than consolidated.

## 3. Contributor Experience

- [ ] **CONTRIBUTING.md exists** — missing.
- [ ] **Code of Conduct** — missing.
- [ ] **Good first issues labeled** — no issues opened yet.
- [ ] **PR template or guidelines** — missing.
- [ ] **Issue templates** — missing.
- [x] **Dev environment setup documented** — `site/README.md` has preview + deploy.
- [n/a] **Tests runnable locally** — no code.
- [n/a] **Response time on issues/PRs** — no issues yet.

## 4. Technical Infrastructure

- [x] **Version control on GitHub** — public, linear history, meaningful commit messages.
- [ ] **Branch protection on main** — not set.
- [~] **CI/CD pipeline** — Pages deploy workflow only; no code to test.
- [ ] **Automated linting/formatting** — no markdownlint / prettier / etc.
- [ ] **Commit notifications** — no public channel.
- [ ] **Issue tracker actively used** — zero issues.
- [ ] **Release automation** — no tags, no releases.
- [n/a] **Dependency updates tracked** — no deps.

## 5. Versioning & Releases

All seven items `[n/a]` — a thinking repo doesn't version its pages.

## 6. Licensing & Legal

- [x] **LICENSE file in repo root** — full CC BY-SA 4.0 text.
- [n/a] **License in package metadata** — no package file.
- [n/a] **License headers in source files** — CC BY-SA doesn't require per-file headers.
- [n/a] **Dependency license compatibility** — no deps.
- [ ] **Contributor agreement approach chosen** — not stated; default would be "contributions inbound-licensed under CC BY-SA 4.0" but nobody reading the repo knows that.
- [~] **Copyright notice present** — LICENSE has standard CC text but no `© 2026 Artem Zhiganov` line anywhere.
- [n/a] **Trademark guidelines** — not that kind of project.

## 7. Governance & Decision-Making

- [ ] **Governance model stated** — implicit "Artem decides," never written down.
- [ ] **Decision-making process documented** — none.
- [ ] **Maintainer roles defined** — single maintainer, not named.
- [ ] **Path to maintainership** — none.
- [ ] **Non-code contributions recognized** — no CONTRIBUTING, so nothing is recognized.
- [x] **Discussions happen in public** — the entire origin doc *is* the seeding conversation made public.

## 8. Communication & Community

- [ ] **Primary communication channel exists** — no Discussions, no email listed, no Telegram/Discord.
- [ ] **Channel linked from README** — n/a until a channel exists.
- [ ] **Discussions archived and searchable** — none.
- [ ] **Announcements process** — none.
- [n/a] **Security vulnerability reporting** — no code surface.
- [ ] **Conventions documented** — commit messages follow a tone but it's not written down.

## 9. Automation & Maintenance

- [n/a] **Automated test suite** — no code.
- [n/a] **Test coverage tracked** — no code.
- [ ] **Stale issue/PR management** — none.
- [n/a] **Automated dependency updates** — no deps.
- [n/a] **Build reproducibility** — no build beyond static site.
- [x] **Monitoring/health dashboard** — GitHub Actions tab shows Pages deploy status.

## 10. Project Health Signals

- [x] **Recent commits** — 7 commits within hours of creation.
- [n/a] **Issues being triaged** — none opened yet.
- [ ] **Multiple contributors** — single-contributor (Artem). Bus factor = 1.
- [~] **Roadmap or milestones** — `concept/commitments.md` tracks Viktor's promised principles draft and ongoing cadence. No broader roadmap.
- [ ] **Users acknowledged** — no reader-facing mention of who this might be for.

## Top Priorities

1. **CONTRIBUTING.md (or a 10-line "How to engage" section in README)** — without it, the project invites conversation (license, tone) but provides no mechanism for it. Biggest gap for a thinking-in-public repo.
2. **One communication channel** — email, GitHub Discussions, or a Telegram link. A reader who wants to respond to framings has nowhere to do so short of opening an unguided Issue.
3. **Explicit copyright + contributor-licensing line** — "© 2026 Artem Zhiganov. Contributions inbound-licensed under the same CC BY-SA 4.0." Closes the legal ambiguity in one sentence.
4. **Named governance** — one paragraph: "This is a personal thinking space maintained by Artem Zhiganov; PRs and Issues welcome; disagreements resolved by conversation or fork." Beats implicit.

## Quick Wins

- Add `© 2026 Artem Zhiganov` below the license block in README
- Enable GitHub Discussions and add one line to README linking it
- Write a 15-line `CONTRIBUTING.md` covering: how to suggest additions, preferred tone, inbound license
- Add a 2-sentence "Governance" section to the README
