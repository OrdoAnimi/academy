# Velocity Academy

Static site for Velocity Academy: the front door and training ground for the wider Velocity Architecture ecosystem.

## Source of truth

GitHub is the source of truth for this site. The public site is the rendered deployment layer.

Repository: `ZenCloudAU/velocity-academy`

Live domain: https://velocityarchitecture.com.au/

## Purpose

Velocity Academy teaches decision-first architecture for the age of AI. It serves architecture leaders, solution architects, enterprise architects, cloud advisors, AI-enabled delivery practitioners, and emerging Design Authorities.

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
| `/start-here/` | Academy purpose, audience, usage, and ecosystem orientation |
| `/pathways/` | Role-based practitioner pathways |
| `/pathways/solution-architecture-practitioner.html` | Solution Architecture Practitioner pathway |
| `/pathways/enterprise-architecture-practitioner.html` | Enterprise Architecture Practitioner pathway |
| `/pathways/ai-enabled-delivery-practitioner.html` | AI-Enabled Delivery Practitioner pathway |
| `/framework/` | Framework concept bridge |
| `/tools/` | Ecosystem tools map |
| `/ecosystem/` | Ecosystem destination map |
| `/courses/` | Course catalogue |
| `/courses/enterprise-architecture-foundations/` | Flagship EA course |
| `/courses/enterprise-architecture-foundations/module-01.html` | Module 1: The ADM Cycle |
| `/courses/enterprise-architecture-foundations/module-02.html` | Module 2: Architecture Vision |
| `/courses/enterprise-architecture-foundations/module-03.html` | Module 3: BDAT Baseline and Gap Analysis |
| `/courses/enterprise-architecture-foundations/module-04.html` | Module 4: Options Paper and Migration Roadmap |
| `/courses/enterprise-architecture-foundations/module-05.html` | Module 5: Component Diagrams |
| `/courses/enterprise-architecture-foundations/module-06.html` | Module 6: Sequence Diagrams |
| `/courses/enterprise-architecture-foundations/module-07.html` | Module 7: Activity and Class Diagrams |
| `/courses/enterprise-architecture-foundations/module-08.html` | Module 8: Reading ArchiMate |
| `/courses/enterprise-architecture-foundations/module-09.html` | Module 9: Current and Target Architecture Views |
| `/courses/enterprise-architecture-foundations/module-10.html` | Module 10: Capability Map and Stakeholder Story |
| `/courses/enterprise-architecture-foundations/module-11.html` | Module 11: Executive Architecture Pack |
| `/courses/enterprise-architecture-foundations/module-12.html` | Module 12: Mock EA Interview and Final Assessment |
| `/library/` | Books, guides, and long-form knowledge |
| `/library/reading-the-map/` | Reading the Map collection |
| `/knowledge/` | Knowledge Portal |
| `/knowledge/series/` | Article series index |
| `/knowledge/articles/` | Article categories |
| `/knowledge/concepts/` | Concept index |
| `/knowledge/concepts/velocity-and-safe.html` | Velocity and SAFe concept note |
| `/knowledge/medium/` | Medium archive index |
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
  start-here/
  pathways/
  framework/
  tools/
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
| Start Here | Live |
| Practitioner pathways | Live |
| Framework bridge | Live |
| Tools map | Live |
| Courses catalogue | Live |
| Enterprise Architecture Foundations | Live |
| EA Foundations modules 1-12 | Live |
| Library | Live |
| Reading the Map collection | Live, expandable |
| Knowledge Portal | Live |
| Resources hub | Live, planned downloads |
| Certification | Pilot / planned |
| Ecosystem map | Live |
| GitHub Build Estate | Live |

## Ecosystem role

```text
ZenCloud advises.
StudioSix produces.
Velocity decides.
```

- ZenCloud: advisory and enterprise engagement
- StudioSix: production, media, publishing, research, AI tools
- Velocity Academy: learning, certification, books, knowledge portal, resources
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

- Verify all live module routes after Cloudflare deployment completes.
- Correct Reading the Map chapter map against the manuscript.
- Add real Medium links to the Knowledge Portal.
- Add downloadable resource files.
- Add concept pages one at a time.
- Keep Series 5 unpublished until ready.
