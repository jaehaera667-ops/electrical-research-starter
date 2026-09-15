# Electrical Research Starter — Design Spec

## Purpose

Build a public, beginner-friendly electrical-engineering research starter repository for a recent EE graduate who wants to learn research through small, simulation-first projects before joining a formal research group.

The repository is not a generic link dump and not an AI-research curriculum. Its job is to answer five practical questions:

1. What research directions exist in electrical engineering?
2. Which tools and open-source projects are worth learning first?
3. What skills actually matter when doing research?
4. How are research outputs evaluated (journals, conferences, GitHub contributions)?
5. What should a beginner do in the first 8 weeks without immediately joining group meetings or attempting an oversized project?

## Audience and constraints

- Primary background: undergraduate electrical engineering.
- Research level: beginner; has course/thesis exposure but no need to assume independent-research experience.
- Preferred entry point: power systems, renewable energy, storage, smart grids, control/optimization; AI is optional rather than mandatory.
- Preferred research mode: computational modelling and simulation are valid first-stage research methods.
- AI may assist coding, literature triage, debugging and writing, but the learner remains responsible for research questions, modelling assumptions, validation and interpretation.
- The first stage must be low-friction: no requirement to attend group meetings, contact professors, submit PRs, or read dozens of papers before running a first model.

## Information architecture

### `README.md`
Landing page: repository purpose, who it is for, quick-start path, directory index, and the minimum first action.

### `ROADMAP.md`
An 8-week starter plan:
- Weeks 1–2: understand the research landscape and run one established tool/example.
- Weeks 3–4: reproduce a small published/standard benchmark case.
- Weeks 5–6: make one controlled modification and compare results.
- Week 7: organize figures, tables and interpretation.
- Week 8: produce a short technical report and decide whether to seek a mentor or expand the project.

### `docs/01-research-map.md`
Map the main EE research areas with emphasis on power/energy: power-system operation and planning, renewable integration, energy storage, smart grids, microgrids, power electronics, machines and drives, control, protection, high voltage, energy markets and electrified transport. Explain typical questions, common methods, and whether hardware is usually required.

### `docs/02-toolbox.md`
Curated tools, not exhaustive. Prioritize tools with strong research relevance and public documentation, such as MATPOWER, pandapower, PyPSA, Grid2Op, OpenDSS, PowerModels.jl, ANDES, and related benchmark/data projects. Mark each as beginner/intermediate/advanced and explain the first useful task to try.

### `docs/03-projects.md`
Curated open-source research projects grouped by entry difficulty. Each entry explains what the project does, why it matters for EE research, what a beginner can learn from it, and what counts as a meaningful contribution. Do not tell a beginner to start by solving upstream issues.

### `docs/04-research-skills.md`
Research skills in workflow order: question framing, literature search, paper reading, modelling, reproduction, experiment design, validation, result interpretation, reproducibility, Git/GitHub, scientific writing, and AI-assisted research practice.

### `docs/05-publication.md`
Explain journals vs conferences, SCIE/ESCI/EI/Scopus/CPCI, JCR Q1–Q4, why conference quality is field-dependent, why “IEEE” is not itself a quality grade, and how GitHub contribution records differ from publication records. Emphasize venue reputation and actual contribution over labels alone.

### `WATCHLIST.md`
A short prioritized list of repositories/organizations worth starring or watching manually because the connected GitHub tooling cannot perform Star/Follow actions.

### `templates/`
- `paper-reading-card.md`: one-page paper reading template.
- `reproduction-log.md`: reproducibility/experiment log.
- `research-question-card.md`: turn an idea into a testable research question.
- `mentor-screening.md`: evaluate a potential paid/unpaid mentor or first research project.

## Editorial rules

- Chinese-first prose; retain standard English technical terms where useful.
- Prefer concise explanations and practical examples over exhaustive theory.
- Label difficulty and recommended first action.
- Separate “learn this now” from “know this exists”.
- Avoid prestige inflation and publication guarantees.
- No recommendation to pay for guaranteed authorship or guaranteed SCI/EI acceptance.
- External links should point to official project repositories/sites when possible.
- The repository should remain useful even if the learner never pursues AI research.

## Success criteria

A beginner should be able to open the repository and, within 10 minutes, identify one suitable EE research direction, one tool to install/run, one small reproducible task, and an 8-week path to a first self-contained research artifact.
