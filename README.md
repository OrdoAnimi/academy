# Velocity Architecture Academy

Static site for the Velocity Architecture Academy: courses, library, knowledge portal, resources, certification, and ecosystem routing for the Velocity Architecture ecosystem.

## Source of truth

GitHub is the source of truth for this site. The public site is the rendered deployment layer.

Repository: `ZenCloudAU/velocity-academy`

Live domain: https://velocityarchitecture.com.au/

## Purpose

Velocity Architecture Academy teaches decision-first architecture for the age of AI. It serves architecture leaders, practitioners, delivery teams, and AI-enabled enterprise teams.

## Deployment

Cloudflare Pages static deployment.

- Build command: none
- Output directory: repository root
- Branch: `main`
- Stack: HTML and CSS only
- Dependencies: none

## Route map

| Route | Purpose |
|---|---|
| `/` | Academy landing page |
| `/site-map.html` | Public route map |
| `/courses/` | Course catalogue |
| `/courses/enterprise-architecture-foundations/` | Flagship EA course |
| `/courses/enterprise-architecture-foundations/module-01.html` | Module 1: The ADM Cycle |
| `/library/` | Books, guides, and long-form knowledge |
| `/library/reading-the-map/` | Reading the Map collection |
| `/knowledge/` | Knowledge Portal |
| `/knowledge/series/` | Article series index |
| `/knowledge/articles/` | Article categories |
| `/knowledge/concepts/` | Concept index |
| `/knowledge/concepts/velocity-and-safe.html` | Velocity and SAFe concept note |
| `/knowledge/medium/` | Medium archive placeholder |
| `/resources/` | Practitioner resources |
| `/certification/` | Pilot certification pathways |
| `/ecosystem/github.html` | GitHub Build Estate |

## Repo structure

```text
/
  index.html
  site-map.html
  style.css
  _redirects
  courses/
  library/
  knowledge/
  resources/
  certification/
  ecosystem/
```

## Content status

| Area | Status |
|---|---|
| University shell | Live |
| Courses catalogue | Live |
| Enterprise Architecture Foundations | Live |
| Module 1 | Live |
| Library | Live |
| Reading the Map collection | Live, expandable |
| Knowledge Portal | Live |
| Resources hub | Live, planned downloads |
| Certification | Pilot / planned |
| GitHub Build Estate | Live |

## Ecosystem role

```text
ZenCloud advises.
StudioSix produces.
Velocity decides.
```

- ZenCloud: advisory and enterprise engagement
- StudioSix: production, media, publishing, research, AI tools
- Velocity Architecture Academy: learning, certification, books, knowledge portal, resources
- Velocity Architecture Framework: framework authority site
- EA Artefact Generator: tool layer

## Link rule

Use root-relative internal links for public routes:

```html
<a href="/courses/">Courses</a>
<a href="/knowledge/">Knowledge</a>
<link rel="stylesheet" href="/style.css">
```

This avoids broken links across nested folders.

## Public data note

Public static site. No user data collected. No backend. No authentication. No cookies or tracking scripts. Plain HTML/CSS, no build system, no dependencies.

## Next steps

- Add Module 2: Architecture Vision.
- Correct Reading the Map chapter map against the manuscript.
- Add real Medium links to the Knowledge Portal.
- Add downloadable resource files.
- Add concept pages one at a time.
- Keep Series 5 unpublished until ready.
