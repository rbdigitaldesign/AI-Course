# AI Literacy Course — First Pass Development Review

**Institution:** University of Adelaide
**Format:** 10-week undergraduate, Canvas LMS, Non-Graded Pass ePortfolio
**Auditor:** Claude Code | **Date:** 2026-03-31 | **Status:** Pre-launch, active development

---

## Course Roadmap

| Week | Topic | Workshop | Portfolio (ongoing) | Project & Poster | Due |
|------|-------|----------|---------------------|-----------------|-----|
| 1 | What is AI? | Demystifying artificial intelligence | Set up portfolio and begin weekly reflections | — | Topic 1 quiz |
| 2 | What can AI do? | What can AI do? | Continue reflections and evidence collection | — | Topic 2 quiz |
| 3 | How can AI be used in education & research? | AI in education & research | Build first portfolio entries and reflections from workshops 1–3 | — | Portfolio checkpoint 1 |
| 4 | The AI project | The AI project | Continue portfolio reflections including project learning | Groups form; define project scope | — |
| 5 | What are the impacts of AI? | The impacts of AI use | Reflections on impacts and responsible use | Develop project ideas; allocate roles | Project plan + Portfolio checkpoint 2 |
| 6 | What are the boundaries of AI use? | IP, regulations and laws | Reflections on responsible AI use | Refine project approach | — |
| 7 | Impacts on cultures, truth and security | Creativity, identity and trust | Critical reflection on bias, culture and trust | Review project progress | Portfolio checkpoint 3 + Topic 7 quiz |
| — | Mid-semester break | — | — | — | — |
| 8 | How can AI be used in the workplace? | AI at work | Workplace application reflection | Develop solution; begin poster planning | Quiz check-in |
| 9 | What problems could we solve with AI? | AI at work | Continue reflections integrating project learning | Draft and refine poster | — |
| 10 | What does the future of AI look like? | AI into the future | Final synthesis reflection | Finalise poster and presentation | Project, poster & final presentation |

---

## What Is Working Well

### Course arc and sequencing
The 10-module progression is logically sound and well-ordered. Foundations (Weeks 1–2) precede application (Weeks 3–4), which precede ethical analysis (Weeks 5–7), which precede professional and futures content (Weeks 8–10). The roadmap above maps cleanly to this arc and the mid-semester break falls at a natural transition point between the responsible-use section and the applications section. No changes needed here.

**Files:** `1-dot-0` through `10-dot-0` — sequencing is consistent throughout.

### Workshop structure
Every module delivers the same reliable workshop format: a timed 6-segment session (summary → discussion → primary activity → feedback → secondary activity + portfolio → wrap-up). Students in Week 8 will navigate the workshop the same way they did in Week 1. This predictability is a genuine strength.

**Files:** `1-dot-4`, `2-dot-4`, `3-dot-4`, `4-dot-4`, `5-dot-4`, `6-dot-3`, `7-dot-3`, `8-dot-3`, `9-dot-3`, `10-dot-3`

### Tone and teaching voice
The writing is consistently conversational and appropriately pitched for a mixed-discipline undergraduate cohort. Technical concepts are explained through strong analogies (image classification via muffins vs chihuahuas in `2-dot-1`; word vector relationships via "king minus churl plus wench" in `2-dot-2`). The voice feels consistent across the majority of the 103 files.

### Ethical framing as a thread — not a module
Rather than isolating ethics in one week, the course weaves responsible use, critique, and reflection throughout every module. This is reinforced in the roadmap via portfolio checkpoints, the project plan (Week 5), and the progressive deepening from impacts → boundaries → culture/trust.

### Assessment design
The ePortfolio + group project + viva triad is well-conceived and authentic. The three portfolio checkpoints (Weeks 3, 5, 7) are well-distributed across the arc and create natural review points that align with the roadmap's three phases. Pass criteria per CLO give students clear targets.

### Design consistency
The callout-box system (`callout-watch`, `callout-interact`, `callout-read`, `guided-activity`, etc.), colour palette, and `N-dot-N-descriptive-name.html` file naming convention are applied consistently across all 103 files. Living style references exist at `page-design-elements.html` and `callout-boxes.html`.

---

## Opportunities for Review

The items below are listed in order of impact on learner experience. File references are included throughout.

---

### 1. Video placeholders — highest priority before launch

Many pages carry `[INSERT VIDEO HERE]` or `[Draft Script for Intro Video]` markers where module introduction and concept-explanation videos should sit. Until these are filled, the course relies entirely on text and the multimedia variety implied by the design is not delivered.

**Files with confirmed video placeholders:**
- `1-dot-0-topic-overview-demystifying-ai.html` — intro video placeholder
- `2-dot-0-topic-overview-what-can-ai-do.html` — intro video placeholder
- `3-dot-0-topic-overview-ai-in-education-and-research.html` — draft script present, video not embedded
- `5-dot-0-topic-overview-the-impacts-of-ai-use.html` — placeholder present
- `7-dot-0-topic-overview-creativity-identity-and-trust-in-the-age-of-ai.html` — placeholder with note: "[might be interesting to make this an AI spoof]"
- `8-dot-0-ai-at-work.html` — placeholder present
- `10-dot-0-a-future-with-ai.html` — Zoom transcript draft present, final video not embedded

**Recommendation:** Prioritise topic overview intro videos first (one per module) as they are the entry point to each week. Guest expert interview videos (referenced in `1-dot-2`, `2-dot-2` etc.) can follow.

---

### 2. Draft author comments visible in production files

A number of files contain internal editorial notes that should not be visible to students. These need to be stripped before any cohort accesses the course.

**Files to check and clean:**
- `7-dot-0-topic-overview-creativity-identity-and-trust-in-the-age-of-ai.html` — contains `[might be interesting to make this an AI spoof of whoever does the rest of the intro videos]`
- `3-dot-0-topic-overview-ai-in-education-and-research.html` — draft script markers present
- `10-dot-0-a-future-with-ai.html` — raw Zoom transcript text with speaker labels visible
- Any file with yellow `#ffff00` highlight — this colour is used as a development placeholder indicator throughout; search for it across all files before launch

---

### 3. Module overview pages — uneven depth

Some topic overview pages are well-developed with clear rationale, framing questions, and context. Others are noticeably thin — little more than a title and brief description — which means students enter those weeks without adequate orientation.

**Thin overview pages to develop:**
- `8-dot-0-ai-at-work.html` — limited framing relative to the complexity of the week's content
- `9-dot-0-how-is-ai-being-used-in-industry.html` — strong stat (hundreds of billions in AI investment) but weak orientation for learners
- `10-dot-0-a-future-with-ai.html` — currently a Zoom transcript draft rather than a polished overview

**Strong overviews to use as a model:**
- `5-dot-0-topic-overview-the-impacts-of-ai-use.html` — "Good, Bad, and Ugly" framing is clear and purposeful
- `6-dot-0-topic-overview-what-are-the-boundaries-of-ai-use.html` — Jurassic Park hook is effective

---

### 4. Module-level learning objectives — verb consistency

Course-level CLOs use precise, assessable Bloom's verbs throughout. Several module-level objectives use weaker verbs ("understand", "learn", "know") that cannot be directly assessed or used by students to self-check readiness.

**Files where module objective verbs should be reviewed:**
- `1-dot-0-topic-overview-demystifying-ai.html` — "Understand course structure" → consider "Navigate course structure and locate..."
- `2-dot-0-topic-overview-what-can-ai-do.html` — "Learn how AI identifies itself" → consider "Identify examples of AI in daily life"
- `3-dot-0-topic-overview-ai-in-education-and-research.html` — "Know AI limitations" → consider "Describe key limitations of current AI tools"
- `8-dot-0-ai-at-work.html` — "Understand AI application design" → consider "Describe the process of designing an AI application"

---

### 5. Content currency — AI-specific risk

For a course about AI, reference currency is more visible than it would be in most subjects. The primary LLM reference is ChatGPT (November 2022), and the tools list in `0-dot-1-the-big-list-of-tools.html` covers 60+ tools, some of which may have changed significantly since the list was compiled.

**Files to review for currency:**
- `2-dot-1-what-can-ai-do.html` and `2-dot-2-how-does-generative-ai-work.html` — update primary LLM exemplar from ChatGPT-3.5 to include current models (GPT-4o, Claude 3/4, Gemini 2.0); the technical explanations remain accurate but the examples date the content
- `0-dot-1-the-big-list-of-tools.html` — audit tool list for deprecated or significantly changed entries; consider a note indicating the list was last reviewed on a specific date
- `9-dot-0-how-is-ai-being-used-in-industry.html` — investment figures and industry examples should be checked against 2024–25 data

---

### 6. Academic integrity guidance — distribution across the roadmap

Module 3 (`3-dot-1` and `3-dot-0`) covers acceptable AI use well. However, given that students begin using AI tools from Week 1 and the group project starts in Week 4, students who engage unevenly with Week 3 content may not encounter the policy before they need it.

**Recommendation:**
- `welcome.html` or `1-dot-0` — add a brief statement on AI use expectations at course entry (Week 1)
- `4-dot-0-topic-overview-the-ai-project.html` — add a reminder at project start (Week 4) covering disclosure requirements for AI-assisted project work
- `temp-assessments.html` / assessment overview page — include AI use policy in the assessment documentation alongside the NGP pass criteria

---

### 7. No learner-facing course map

The roadmap above exists (as shared by you), but there is no equivalent available to students within the course itself. Students navigate week-to-week without being able to see the full shape of what they are working through.

**File to update:**
- `welcome.html` — embed the roadmap table (or a simplified visual version) so students can orient themselves to the full arc from day one. The three phases (Foundations / Responsible Use / Applications) and the mid-semester break are natural dividers that would work well as visual anchors.

---

### 8. Assessment overview page unpublished

Students have no single place to review submission expectations, deadlines, and feedback timelines.

**File to complete and publish:**
- `temp-assessments.html` (currently unpublished) — resolve all `???` placeholders; add submission windows for portfolio checkpoints (Weeks 3, 5, 7) and the final project/poster (Week 10); confirm feedback turnaround commitments; then publish

---

### 9. Backup and draft files in the production repository

The repository contains development variants that should not be accessible to students or confused with production files.

**Files to archive or remove from the main branch:**
- `1-dot-0-topic-overview-demystifying-ai-backup.html`
- `1-dot-1-what-is-ai-concept.html`
- `1-dot-3-student-presentations-deleted.html`
- `5-dot-0-topic-overview-the-impacts-of-ai-use-copy.html`
- `development-test-page.html`
- All `do-not-publish-tutor-instructions-week-*.html` files (Weeks 1–6) — these are well-written and valuable; they just need to be confirmed as not student-visible in Canvas

---

### 10. No glossary

Technical terms (LLM, neural network, word vector, affine transform, generative AI) are defined well at their point of introduction, but there is no reference page students can consult when they encounter a term in Week 7 that was first defined in Week 2.

**File to create:**
- `0-dot-4-glossary.html` — a single alphabetical reference page linked from the welcome page and from the first use of each term in module content. Given the technical density of the subject, this would have high utility as a standalone reference tool.

---

## Summary

| Area | Status | Primary Files |
|------|--------|--------------|
| Course arc & sequencing | Ready | All `*-dot-0` overview files |
| Workshop structure | Ready | All `*-dot-4` / `*-dot-3` workshop files |
| Tone & voice | Ready (minor cleanup needed) | All — strip draft comments |
| Ethical threading | Ready | Modules 5, 6, 7 especially |
| Assessment design | Needs completion | `temp-assessments.html` |
| Video content | Not yet complete | All `*-dot-0` topic overviews |
| Module objectives | Needs verb audit | `1-dot-0`, `2-dot-0`, `3-dot-0`, `8-dot-0` |
| Content currency | Needs refresh | `2-dot-1`, `2-dot-2`, `0-dot-1` |
| Course map for students | Missing | `welcome.html` |
| Academic integrity distribution | Gaps | `welcome.html`, `4-dot-0`, assessment page |
| Glossary | Missing | Create `0-dot-4-glossary.html` |
| Draft/backup file cleanup | Needs action | Multiple — see Section 9 above |
