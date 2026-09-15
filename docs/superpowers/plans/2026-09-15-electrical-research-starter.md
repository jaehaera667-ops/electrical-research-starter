# Electrical Research Starter Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a concise, beginner-friendly public repository that helps an electrical-engineering graduate take the first steps into research through simulation-first, reproducible projects.

**Architecture:** Markdown-first knowledge base with a single landing page, one 8-week roadmap, five focused reference guides, one watchlist, and reusable research templates. External links point to official repositories/sites; content is Chinese-first and separates immediate actions from later-stage options.

**Tech Stack:** GitHub, Markdown, public EE research repositories and documentation.

**Spec:** `docs/superpowers/specs/2026-09-15-electrical-research-starter-design.md`

## Global Constraints

- Chinese-first prose; preserve useful English technical terms.
- Power/energy EE is the default path; AI is optional.
- Simulation and computational experiments are valid first-stage research methods.
- Do not require group meetings, professor outreach, upstream PRs, or dozens of papers in the first stage.
- No guaranteed-publication claims and no paid-authorship recommendations.
- Prefer official project links.

---

### Task 1: Landing page and 8-week roadmap

**Files:**
- Create: `README.md`
- Create: `ROADMAP.md`

**Produces:** A 10-minute onboarding path and a week-by-week first research cycle.

- [ ] Create README with scope, quick start, directory index, and “do this first” section.
- [ ] Create an 8-week roadmap from tool familiarization through reproduction, one controlled extension, analysis, and a short technical report.
- [ ] Verify README links to planned files use correct relative paths.
- [ ] Commit.

### Task 2: EE research map

**Files:**
- Create: `docs/01-research-map.md`

**Produces:** A practical map of EE research directions with typical questions, methods, software, and hardware dependence.

- [ ] Cover power systems, renewable integration, storage, smart grids/microgrids, energy markets, electrified transport, power electronics, machines/drives, control, protection, and high voltage.
- [ ] Add “beginner fit” and “hardware dependence” guidance.
- [ ] Mark power-system/energy optimization as the recommended starter path.
- [ ] Commit.

### Task 3: Research toolbox and open-source projects

**Files:**
- Create: `docs/02-toolbox.md`
- Create: `docs/03-projects.md`
- Create: `WATCHLIST.md`

**Produces:** A curated tool/project ladder and a manual star/watch list.

- [ ] Add MATPOWER, pandapower, PyPSA, Grid2Op, OpenDSS, PowerModels.jl, ANDES, and SimBench where appropriate.
- [ ] For each tool, state difficulty, what it is best for, and one first task.
- [ ] Separate beginner “run/modify examples” from later “contribute upstream”.
- [ ] Create watchlist with official repository links and reasons to follow.
- [ ] Commit.

### Task 4: Research skills and AI-assisted workflow

**Files:**
- Create: `docs/04-research-skills.md`

**Produces:** A workflow-oriented skills guide.

- [ ] Explain question framing, literature search, paper reading, modelling, reproduction, experiment design, validation, interpretation, reproducibility, Git/GitHub, and writing.
- [ ] Define appropriate AI roles: implementation assistance, literature triage, debugging, plotting, drafting.
- [ ] Define human responsibilities: research question, assumptions, correctness checks, experiment fairness, result interpretation, claims.
- [ ] Include a “minimum skill before first project” checklist.
- [ ] Commit.

### Task 5: Publication and contribution evaluation

**Files:**
- Create: `docs/05-publication.md`

**Produces:** A concise map of academic-output evaluation.

- [ ] Explain journal vs conference and indexing vs quality.
- [ ] Explain SCIE/ESCI/EI/Scopus/CPCI and JCR Q1–Q4 at a practical level.
- [ ] Explain why IEEE is a publisher/professional organization, not a quality grade by itself.
- [ ] Explain GitHub contribution signals: issue, PR, review, merge, release, maintainer, software paper.
- [ ] Add red flags for “guaranteed EI/SCI”, vague “Q1 conference”, and paid authorship.
- [ ] Commit.

### Task 6: Reusable research templates

**Files:**
- Create: `templates/paper-reading-card.md`
- Create: `templates/reproduction-log.md`
- Create: `templates/research-question-card.md`
- Create: `templates/mentor-screening.md`

**Produces:** Four lightweight templates a beginner can actually use.

- [ ] Keep each template to one page or less.
- [ ] Make the reproduction log record environment, inputs, expected result, actual result, deviations, and next action.
- [ ] Make mentor screening focus on who actually mentors, meeting cadence, learner contribution, ownership, authorship criteria, and publication promises.
- [ ] Commit.

### Task 7: Repository verification

**Files:**
- Review all Markdown files.

**Produces:** A coherent public repository with no broken internal navigation or contradictory advice.

- [ ] Verify all relative links and official project URLs.
- [ ] Check terminology consistency: JCR Q1–Q4, EI Compendex, simulation/numerical experiment, PR/merge.
- [ ] Check the roadmap never requires premature group meetings, outreach, or upstream contribution.
- [ ] Check README provides a usable first action within 10 minutes.
- [ ] Make any final corrections and commit.
