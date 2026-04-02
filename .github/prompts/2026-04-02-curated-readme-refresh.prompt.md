---
agent: agent
description: Redesign profile README into a curated narrative-professional format for recruiter-first scanning.
---

## Context
The existing profile README is content-rich but too long and repetitive for fast recruiter scanning. The goal is to keep authenticity and impact while replacing the current vibe-heavy structure with a curated, professional presentation that remains personal and credible.

## Decision
Implement an impact-first narrative layout: concise positioning at the top, measurable proof points early, compact project summaries, curated stack categories, and a short background section with low emphasis on student status. Preserve flagship credibility (`agents-templated`) and measurable outcomes (museum workflow reduction) while removing repeated messaging and visual clutter.

## Steps
1. Audit current README sections and keep only high-signal content.
2. Define a new section order for recruiter-first scanning with narrative tone.
3. Rewrite hero, proof points, featured project, and selected project summaries.
4. Replace long technology dumps with curated categories.
5. Add concise personal background and contact CTA.
6. Validate final length, readability, and link integrity.

## Acceptance Criteria
- README communicates identity, strengths, and impact in the top section without scrolling far.
- Content is curated and non-repetitive with clear section purposes.
- Student status appears only once with low emphasis.
- Flagship package and top projects are presented with measurable outcomes.
- Final README stays roughly within 80-130 lines and is easy to skim on GitHub.

## Status
- [ ] Not started
- [ ] In progress
- [x] Complete
Blockers (if any): None
