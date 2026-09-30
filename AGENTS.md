# Velocity Academy Agent Instructions

## Product Purpose

Velocity Academy is the front door and training ground for the Velocity Architecture ecosystem. It helps enterprise architects, solution architects, cloud advisors, AI-enabled delivery practitioners, and emerging Design Authorities move from learning concepts to applying frameworks, producing artefacts, assessing readiness, and operating inside governed delivery environments.

This repository is a static HTML/CSS site. Prefer simple front-end implementation unless the repo later establishes a backend pattern.

## UX Principles

- Position the Academy as the learning layer for an architecture capability ecosystem, not a generic course site.
- Keep the homepage clear enough for a new visitor to understand the Academy immediately.
- Keep pathway selection reachable within two clicks from the homepage.
- Use concise, practical, executive-practitioner language.
- Preserve the existing visual system unless a requested change requires local styling support.
- Avoid generic e-learning phrasing that does not connect to enterprise delivery, artefacts, readiness, or governance.

## Routing Conventions

- Use root-relative links for public routes, for example `/pathways/` and `/framework/`.
- Top-level navigation should include: Start Here, Pathways, Framework, Tools, Certifications, Ecosystem.
- Keep existing supporting routes such as `/courses/`, `/library/`, `/knowledge/`, `/resources/`, and `/dashboard/` available unless explicitly deprecated.
- Use `_redirects` for clean trailing-slash routes and legacy route compatibility.

## Component Conventions

- Reuse the existing CSS classes: `hero`, `container`, `section-alt`, `section-dark`, `cards-grid`, `card`, `card-head`, `badge`, `teach-grid`, `eco-grid`, and `footer-inner`.
- Add small utility classes only when they reduce repeated inline styles or support repeatable page structure.
- Keep static pages dependency-free. Do not add a JavaScript framework or build system without an explicit reason.

## Content Conventions

- Every pathway page should include target audience, outcomes, prerequisites, recommended modules, practice exercises, artefacts produced, related ecosystem tools, and a next step.
- Module pages should follow this structure where practical: learning outcome, why it matters in enterprise delivery, core concepts, practical exercise, artefact or evidence produced, related framework concepts, related tools, and next module.
- Treat artefacts as evidence for delivery, review, readiness, and certification preparation.
- Keep content concise and specific to architecture practice.

## Cross-Linking Rules

- Link Academy pages to ecosystem destinations only when the destination is relevant to the learning action.
- Logical ecosystem destinations include:
  - `ordo-animi` as the brain and coordinating intelligence layer.
  - `exec.velocityarchitecture.com.au` as the executive operating surface.
  - `velocity-architecture` for the framework and decision system.
  - `vaf-sa` for the solution architecture practitioner framework.
  - `ea-artefact-generator`, `sa-artefact-generator`, `ba-artefact-generator`, and `pm-artefact-generator` for artefact production.
  - `pmi-portal` for intake, governance, artefact lifecycle, client transparency, and execution visibility.
  - `vsf-match` for readiness scoring and personalised learning paths.
  - Certification repositories for Azure SA, SAP EA, CISSP, Agentic AI, and AI-assisted coding or delivery learning.
- Do not invent uncertain live destinations. Prefer GitHub repository links or existing public URLs when a production URL is not confirmed.

## Out Of Scope

- Do not add token usage tracking.
- Do not add cost modelling, consumption dashboards, pricing calculators, billing mechanics, or AI usage analytics.
- Do not add heavy backend functionality.
- Do not collect user data unless a future task explicitly adds a governed data model.

## Acceptance Criteria

- A new visitor can immediately understand what Velocity Academy is.
- A practitioner can choose a pathway within two clicks.
- Each pathway connects learning to framework, tools, artefacts, readiness, and next action.
- Navigation links resolve where possible.
- No filler draft text remains.
- The site remains static, dependency-free, and consistent with the existing visual language.
