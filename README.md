# Velocity Architecture Academy

Static site for the Velocity Architecture Academy — the learning, certification, books, lexicon, and practitioner pathway site for the Velocity Architecture ecosystem.

## Purpose

Teaches the decision-first architecture method for the age of AI. Serves architecture leaders, practitioners, and AI-enabled delivery teams.

## Target domain

**velocityarchitecture.com.au**

> **Note:** This domain currently forwards to the EA Artefact Generator. It will be repointed to this site once the Academy is production-ready and Cloudflare DNS is updated.

## Current status

| Section | Status |
|---|---|
| Site scaffold | Complete |
| Hero | Complete |
| Learning paths (7) | Complete |
| Certification pathways (6) | Complete |
| Velocity Library (7 tracks) | Complete |
| Practitioner resources (8) | Complete |
| Ecosystem section | Complete |
| Actual course content / PDFs / lessons | Not started |
| LMS / enrolment flow | Not started |

## Local preview

```
start index.html
```

Opens in default browser. No build step. No server required.

## Deployment

Intended for **Cloudflare Pages**.

- Build command: none (static HTML)
- Output directory: `/` (root)
- Branch: `main`

Once ready, repoint `velocityarchitecture.com.au` in Cloudflare DNS from its current target to this Cloudflare Pages deployment.

## Ecosystem role

```
velocityarchitecture.com.au         → Academy / learning / certification  (this repo)
velocityarchitectureframework.com   → Framework authority site
ea.velocityarchitecture.com.au      → EA Artefact Generator tool
ZenCloud                            → Advisory and enterprise engagement
StudioSix                           → Product, media, publishing, research, AI tools
```

**Ecosystem line:** ZenCloud advises. StudioSix produces. Velocity decides.

## Public / private data note

Public static site. No user data collected. No backend. No authentication. No cookies or tracking scripts. Plain HTML/CSS, no build system, no dependencies.

## Next steps

- [ ] Add actual course content pages per learning path
- [ ] Create certification enrolment flow or link to external LMS
- [ ] Populate Velocity Library with real book and essay links
- [ ] Add practitioner resource download links
- [ ] Wire VAF Agentic AI and PMO Portal cards to live URLs once available
- [ ] Enable Cloudflare Pages deployment and repoint DNS
- [ ] Add Open Graph and social meta tags
- [ ] Review copy with ZenCloud / StudioSix stakeholders
- [ ] Add Google Analytics or privacy-respecting analytics once domain is live
