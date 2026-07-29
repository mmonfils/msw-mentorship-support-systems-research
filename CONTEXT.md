---
layout: default
title: Context | MSW Mentorship & Critical Pedagogy Research Repository
nav_order: 1
---

# CONTEXT.md | MSW Mentorship & Critical Pedagogy Research Repository

## Project Identity & Metadata
* **Repository Name**: `msw-mentorship-support-systems-research`
* **Repository URL**: `https://github.com/mmonfils/msw-mentorship-support-systems-research`
* **Title**: Mentorship as a Catalyst: Exploring Support Systems in Master of Social Work Graduate Training
* **Event & Context**: Academic research, facilitator resources, and institutional policy documentation supporting the 2026 NASW Iowa Symposium workshop
* **Target Audience**: Academic faculty, field instructors, social work researchers, policy analysts, and conference facilitators
* **Documentation Engine**: Jekyll with the "Just the Docs" theme

## Theoretical & Analytical Lenses
All research papers, policy briefs, and curriculum guides housed in this repository are evaluated through these primary frameworks:
* **Critical Pedagogy (Freirean Praxis)**: Analyzing educational structures to challenge traditional "banking" models and foster problem-posing dialogue.
* **Systems Theory (Person-in-Environment)**: Examining the MSW student experience across micro, mezzo, and macro systems, including institutional barriers and remote learning dynamics.
* **Strengths-Based Approach**: Grounding support models in student assets, resilience, and experiential knowledge rather than deficit frameworks.
* **Proactive Mentorship**: Designing institutional systems that automate outreach and embed support directly into the graduate training process.

## Repository Purpose & Content Scope
This repository serves as the central academic archive and facilitator portal for the mentorship research project. It is decoupled from the live workshop feedback hub to ensure clean separation between participant-facing tools and backend documentation.

### Core Directory Contents
* **`research/`**: Houses primary academic literature, methodological notes, and the core research paper (`research/paper-core.md`).
* **`facilitator/`**: Contains workshop facilitation plans, time-keeper guides, and direct links to live data synthesis views.
* **`standards/`**: Detailed mapping files linking workshop modules to CSWE EPAS Competencies (1, 2, and 9) and NASW Code of Ethics Standards (1.01, 1.05, 2.05, 3.02).
* **`references.md`**: Master citation list and annotated bibliography.

## Source of Truth Reference Map
* **Primary Academic Authority**: `research/paper-core.md`
* **Role**: All theoretical assertions, research data, citation lists, and policy recommendations stored across this site must align directly with the findings in `paper-core.md`.

## Just the Docs Architecture & UI Rules
* **Base Theme**: `just-the-docs` Jekyll gem or remote theme.
* **Navigation Hierarchy**: Use YAML front matter (`parent`, `nav_order`, `has_children`) to maintain clear sidebar navigation across deep research layers.
* **Search Integration**: Built-in Lunr.js search enabled across all Markdown documentation files.
* **Formatting Restrictions**:
    * No emojis: Maintains a clean, academic aesthetic.
    * No em dashes: Standard hyphens or commas must be used exclusively to guarantee uniform browser rendering.
    * Plain Text Diagrams: ASCII flowcharts render structural logic without requiring heavy image assets.
* **Pathing**: Use relative pathing (`./`) throughout all markdown links to ensure compatibility with GitHub Pages rendering.