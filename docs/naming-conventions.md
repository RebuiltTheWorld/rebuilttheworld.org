# Naming Conventions
## rebuilttheworld.org
### Version: v0.1

---

## Purpose

This document defines the naming rules for `rebuilttheworld.org`.

Its purpose is to create consistency across:

- repository structure
- files and folders
- page slugs
- content types
- metadata
- versions
- archive materials

A naming system is not only for convenience.  
It is part of the long-term readability and maintainability of the project.

---

## Core Principle

Names should be:

- clear
- stable
- readable
- predictable
- scalable
- archive-friendly

A good name should help answer three questions:

1. What is this?
2. Where does it belong?
3. How should it relate to other parts of the system?

---

## Naming Goals

The naming system should support:

- long-term clarity
- future collaboration
- easy navigation
- version awareness
- archive integrity
- low ambiguity
- structured growth

Names should not depend on memory alone.

---

## Global Naming Rules

### 1. Use lowercase by default
Use lowercase for folders, files, and slugs.

Preferred:
- `site-structure.md`
- `brand-core.md`
- `human-ai-lab.md`

Avoid:
- `SiteStructure.md`
- `Brand_Core.md`
- `HumanAILab.MD`

### 2. Use kebab-case
Use hyphens (`-`) to separate words.

Preferred:
- `content-system.md`
- `naming-conventions.md`
- `entry-paths.md`

Avoid:
- `content_system.md`
- `contentSystem.md`
- `content system.md`

### 3. Avoid spaces
Do not use spaces in filenames, folder names, or slugs.

### 4. Avoid special characters
Do not use accented characters or special symbols in technical names.

Avoid in filenames/slugs:
- `á é í ó ö ő ú ü ű`
- `&`
- `+`
- `'`
- `"`
- `?`
- `!`
- `,`
- `:`

Use instead:
- `and` instead of `&`
- `ai` instead of `A.I.`
- `human-ai-lab` instead of `Human & AI – LAB`

### 5. Prefer full words over unclear abbreviations
Use short abbreviations only if they are already core to the system.

Allowed when clearly established:
- `rtw`
- `lab`
- `api`
- `ui`
- `url`

Avoid introducing unexplained abbreviations.

---

## Naming Style by Layer

The system should distinguish between:

- **human-facing titles**
- **repository-facing filenames**
- **web-facing slugs**
- **metadata identifiers**

These do not always need to be identical.

Example:

- Human-facing title: `Human & AI LAB`
- Filename: `human-ai-lab.md`
- Slug: `/lab/human-ai-lab`
- Identifier: `lab-human-ai-lab`

---

## Folder Naming Rules

Folder names should be:

- lowercase
- kebab-case when multi-word
- broad enough to remain useful over time
- not overly specific unless the folder is intentionally scoped

Preferred examples:
- `docs`
- `content`
- `pages`
- `manifesto`
- `signals`
- `archive`
- `lab`
- `metadata`
- `references`
- `versions`

Avoid:
- `misc`
- `other`
- `new-folder`
- `stuff`
- `temp-final-new`

If a folder cannot be clearly named, it likely should not exist yet.

---

## File Naming Rules

File names should be:

- lowercase
- kebab-case
- descriptive but not overly long
- stable over time
- aligned with the content role

Preferred examples:
- `brand-core.md`
- `site-structure.md`
- `content-system.md`
- `archive-standard.md`
- `signals-format.md`

Avoid:
- `notes1.md`
- `final-final.md`
- `homepage-new-version.md`
- `draft2-really-final.md`

---

## Document Naming Logic

Documents inside `docs/` should describe systems, not temporary moods.

Preferred patterns:
- `{topic}.md`
- `{topic}-{scope}.md`

Examples:
- `brand-core.md`
- `site-structure.md`
- `content-system.md`
- `naming-conventions.md`
- `editorial-guidelines.md`
- `archive-standard.md`

Do not encode temporary working states in filenames unless absolutely necessary.

Avoid:
- `brand-core-new.md`
- `site-structure-final-v2.md`

Versioning should be handled in metadata or document content, not in the filename by default.

---

## Page Naming Rules

Pages should have three layers of naming:

### 1. Page title
Human-readable and expressive.

Examples:
- `Manifesto`
- `Human & AI LAB`
- `Archive`
- `Signals`

### 2. Internal filename
Repository-safe technical name.

Examples:
- `manifesto.md`
- `human-ai-lab.md`
- `archive.md`
- `signals.md`

### 3. URL slug
Public-facing path.

Examples:
- `/manifesto`
- `/lab/human-ai-lab`
- `/archive`
- `/signals`

---

## Slug Rules

Slugs should be:

- short
- readable
- lowercase
- kebab-case
- stable once published

Preferred:
- `/about`
- `/manifesto`
- `/system`
- `/lab`
- `/archive`
- `/projects`
- `/signals`
- `/entry`

Avoid:
- `/about-us-page`
- `/the-manifesto-of-rebuilt-the-world`
- `/system_v2`
- `/lab!`

### Slug Stability Rule
Once a slug is public, it should not be changed without a redirect plan.

This is important for:

- continuity
- linking
- archives
- future references
- public readability

---

## Content Type Naming

Content types should use consistent names across docs, content, and metadata.

Preferred canonical names:
- `page`
- `manifesto`
- `project`
- `signal`
- `archive-item`
- `field-note`
- `release`
- `reference`
- `document`

Avoid creating many near-duplicate labels such as:
- `note`
- `notes`
- `memo`
- `fragment`
- `journal`
- `entry`

unless their distinctions are clearly defined.

---

## Signal Naming Rules

Signals should remain lightweight, but their names should still be structured.

### Preferred signal filename pattern
`yyyy-mm-dd-short-topic.md`

Examples:
- `2026-03-13-first-structural-pass.md`
- `2026-03-13-readme-and-license-complete.md`
- `2026-03-14-homepage-direction-note.md`

### Signal title pattern
Human-readable and concise.

Examples:
- `First Structural Pass`
- `README and License Complete`
- `Homepage Direction Note`

### Why date-first?
Because signals are time-aware and often read in sequence.

---

## Archive Naming Rules

Archive items should prioritize traceability and long-term clarity.

### Preferred archive filename pattern
`yyyy-mm-dd-topic-type-vx.y.md`

Examples:
- `2026-03-13-brand-core-foundation-v0.1.md`
- `2026-03-13-site-structure-draft-v0.1.md`
- `2026-03-14-manifesto-outline-v0.1.md`

### Archive item fields should ideally reflect:
- date
- topic
- type
- version

This makes archive browsing and future reference easier.

---

## Version Naming Rules

Use semantic-style versions for structured documents.

Preferred:
- `v0.1`
- `v0.2`
- `v1.0`
- `v1.1`

### Suggested meaning
- `v0.x` = early draft / evolving structure
- `v1.0` = first stable public version
- `v1.x` = stable improvements
- `v2.0` = major structural revision

### Important rule
Keep version info inside the document and metadata when possible.

Do **not** put versions into filenames by default unless:

- the item is archive-oriented
- multiple public versions must coexist
- the file is a release artifact

---

## Date Naming Rules

Use ISO-style dates:

`YYYY-MM-DD`

Preferred:
- `2026-03-13`
- `2026-04-01`

Avoid:
- `13-03-2026`
- `03-13-2026`
- `March-13-2026`

This reduces ambiguity across countries, systems, and future readers.

---

## Status Naming Rules

Use a small, consistent set of status words.

Preferred canonical statuses:
- `draft`
- `active`
- `stable`
- `archived`
- `superseded`

These should be used consistently across:
- content metadata
- internal tracking
- archive logic
- documentation references

Avoid ad hoc status labels like:
- `almost-done`
- `working-ish`
- `temporary-final`
- `kind-of-ready`

---

## Project and Module Naming Rules

Project and module names should be consistent across public and internal layers.

### Public naming may preserve style:
- `Human & AI LAB`
- `Rebuilt The World`
- `Timeline Lab`

### Repository-safe naming should normalize:
- `human-ai-lab`
- `rebuilt-the-world`
- `timeline-lab`

### Module identifiers may use scoped prefixes where needed:
- `lab-human-ai`
- `project-timeline-lab`
- `archive-field-notes`

Only introduce prefixes when they help classification.

Do not over-prefix everything.

---

## Asset Naming Rules

Assets should be named for retrieval, not for emotion.

Preferred patterns:
- `{topic}-{type}.{ext}`
- `{topic}-{variant}.{ext}`
- `{date}-{topic}-{type}.{ext}`

Examples:
- `rtw-wordmark.svg`
- `human-ai-lab-icon.svg`
- `homepage-system-map.png`
- `2026-03-13-homepage-wireframe.png`

Avoid:
- `image1.png`
- `final-logo-new.png`
- `screenshot-last-one.png`

### Image folders
Use folders by role, not by mood.

Preferred:
- `public/images/brand/`
- `public/images/projects/`
- `public/images/archive/`
- `public/images/pages/`

---

## Metadata Naming Rules

Metadata should be explicit and stable.

Preferred keys:
- `title`
- `slug`
- `date`
- `version`
- `status`
- `type`
- `summary`
- `related`
- `updated`
- `author`

Avoid inconsistent alternates like:
- `pageTitle`
- `doc_name`
- `currentState`
- `descShort`

Choose one naming style for metadata and stay consistent.

### Recommended metadata key style
Use lowercase, simple keys.

Example:
```yaml
title: Human & AI LAB
slug: /lab/human-ai-lab
date: 2026-03-13
version: v0.1
status: draft
type: project
summary: Public-facing overview of the Human & AI LAB module.
