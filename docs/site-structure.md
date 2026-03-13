# Site Structure
## rebuilttheworld.org
### Version: v0.1

---

## Purpose

This document defines the initial structural logic of `rebuilttheworld.org`.

Its purpose is to clarify:

- what the site is meant to do
- how the public-facing website should be organized
- how users should enter and move through the system
- how the site connects to the broader **Rebuilt The World** ecosystem

This is a foundational structure document, not a final implementation spec.

---

## Core Definition

Current working definition:

> **rebuilttheworld.org = gateway + manifesto + system map + archive entry point**

The site should not behave as a generic marketing homepage.

It should function as a structured public interface for:

- orientation
- meaning
- navigation
- continuity
- documentation
- long-term readability

---

## Structural Principles

The site structure should follow these principles:

### 1. Clarity over noise
The structure must remain readable and understandable at a glance.

### 2. System before decoration
Visual design should support structure, not replace it.

### 3. Entry before depth
The homepage should orient visitors and guide them toward deeper layers.

### 4. Long-term intelligibility
The site should remain understandable for future readers, not only current collaborators.

### 5. Modular growth
The structure should support future expansion without becoming chaotic.

### 6. Archive-aware design
Important content should be preservable, referenceable, and version-aware.

---

## Primary Role of the Homepage

The homepage should not attempt to explain everything.

Its job is to:

- establish identity
- communicate mission
- show the core map
- provide entry paths
- create a stable first orientation layer

The homepage is the **entry surface**, not the entire archive.

---

## Top-Level Site Areas

The current site structure is expected to evolve around these main areas:

- **Home**
- **About**
- **Manifesto**
- **System**
- **LAB**
- **Archive**
- **Projects**
- **Signals**
- **Entry**

Each area has a distinct function.

---

## 1. Home

### Role
The public entry point and first orientation layer.

### Main blocks
- Hero
- Mission
- Core statement
- System map
- Entry paths
- Featured modules
- Latest signals
- Archive access

### Purpose
The homepage should answer:

- What is this?
- Why does it exist?
- What kind of system is this?
- Where should I go next?

---

## 2. About

### Role
Defines what **Rebuilt The World** is and why it exists.

### Expected contents
- project definition
- background
- long-term vision
- purpose
- intended continuity
- relation to broader RTW ecosystem

### Purpose
This page should provide narrative and conceptual grounding.

---

## 3. Manifesto

### Role
States the core principles of the project.

### Expected contents
- core beliefs
- reconstruction logic
- human–AI position
- continuity and legacy framing
- public philosophical direction

### Purpose
This page should explain the project’s deeper logic, not just its surface structure.

---

## 4. System

### Role
Makes the internal structure legible.

### Expected contents
- system map
- module overview
- naming conventions
- documentation principles
- versioning logic
- content relationships

### Purpose
This page should show how the project is organized and how the parts connect.

---

## 5. LAB

### Role
Public-facing layer of **Human & AI LAB**.

### Expected contents
- methods
- experiments
- active directions
- notes
- process fragments
- working logic

### Purpose
This section should present living thought and collaborative experimentation.

---

## 6. Archive

### Role
Structured access point for preserved materials.

### Expected contents
- documents
- field notes
- releases
- records
- verification-related materials
- timeline references

### Purpose
This section should be durable, navigable, and reference-friendly.

---

## 7. Projects

### Role
Shows connected RTW modules and subprojects.

### Expected contents
- project cards
- linked modules
- short definitions
- status indicators
- relation to RTW

### Purpose
This section should help visitors understand the larger ecosystem.

---

## 8. Signals

### Role
Lightweight public notes and active traces of development.

### Expected contents
- short updates
- fragments
- breadcrumbs
- thought markers
- research signals

### Purpose
This area keeps the site alive without requiring every update to become a full archive document.

---

## 9. Entry

### Role
A directional layer for different reader types.

### Expected contents
- paths for collaborators
- paths for future readers
- paths for researchers
- paths for archive-oriented visitors
- paths for first-time visitors

### Purpose
Different users need different entry routes. This section should reduce friction.

---

## User Entry Logic

The site should support multiple reading modes.

### Entry Type A — First-time visitor
Needs orientation, definition, and a clear path.

Suggested route:
`Home -> About -> Manifesto -> Projects`

### Entry Type B — Research-oriented visitor
Needs structure, notes, archive, and references.

Suggested route:
`Home -> System -> LAB -> Archive -> Signals`

### Entry Type C — Future reader / legacy reader
Needs continuity, context, and preserved meaning.

Suggested route:
`Home -> About -> Manifesto -> Archive`

### Entry Type D — Collaborator
Needs structure, active modules, and working directions.

Suggested route:
`Home -> System -> Projects -> LAB -> Entry`

---

## Recommended Navigation Logic

The navigation should feel like a **map**, not only a menu.

### Primary navigation
- Home
- About
- Manifesto
- System
- LAB
- Archive
- Projects
- Signals
- Entry

### Secondary navigation
Can later include:
- timeline
- documents
- methods
- glossary
- verification
- releases

### Footer layer
Should eventually include:
- version
- last updated
- documentation note
- licensing references
- archive policy
- repository references

---

## Homepage Structural Draft

### Suggested order

#### 1. Hero
Short defining statement.

#### 2. Mission
Why the project exists.

#### 3. Core Definition
A concise framing of what RTW is.

#### 4. System Map
A visual or structured overview of the ecosystem.

#### 5. Entry Paths
Different routes for different readers.

#### 6. Featured Modules
Key sections such as LAB, Archive, Manifesto, Projects.

#### 7. Latest Signals
Recent notes, fragments, or visible movement.

#### 8. Archive Access
Path toward preserved materials and deeper documentation.

---

## Content Architecture Logic

The site structure should support three content depths:

### Layer 1 — Orientation
Short, stable, public-facing.

Examples:
- homepage intro
- section overviews
- one-line definitions

### Layer 2 — Interpretation
More detailed pages that explain the system.

Examples:
- About
- Manifesto
- System

### Layer 3 — Preservation
Structured and referenceable materials.

Examples:
- Archive
- field notes
- releases
- documentation records

---

## Page Template Standard

Important pages should follow a shared internal template:

1. Title  
2. One-line definition  
3. Purpose  
4. Context  
5. Main content  
6. Related modules  
7. Version  
8. Archive references  

This should become a stable content standard across the site.

---

## Relationship to Repository Structure

This site structure should later connect to repository folders such as:

```text
docs/
content/pages/
content/manifesto/
content/signals/
content/archive/
content/lab/
metadata/versions/
metadata/references/
