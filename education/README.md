# Wine Education — WSET Level 3 study hub

This folder is a self-study tutor pack for the **WSET Level 3 Award in Wines**. It is platform-agnostic: any AI agent or tutor can use it, in voice mode or in text mode. It tracks what has been *discussed*, what has been *practised*, what needs *review*, and what is *demonstrably mastered*.

## ⚠️ First step for every new learner: copy this pack to your own repo

**Do not study in the shared copy.** Before your first lesson, copy/fork this repository into your own account, so your progress stays yours and does not get mixed with anyone else's or with the shared material.

1. Copy/fork this repo to your own account (for example, on GitHub: Fork, or copy the `education/` folder into a new private repo).
2. In your own copy, copy the blank templates from `education/progress-templates/` into `education/` as `STATE.md`, `PROGRESS.md` and `SESSION_LOG.md`.
3. Give your agent your own repo (or the `education/` folder) and start at Chapter 1, unless your own `STATE.md` says otherwise.

Agents: you are responsible for telling each new learner to do this, before you start teaching. If you cannot write to the learner's repo, give them a copyable log entry after each session instead (see `VOICE-MODE-GUIDE.md`).

## Start here
- **[AGENTS.md](AGENTS.md) — START HERE FOR AI TUTORS:** narrative-first structured tutoring, diagnostics one at a time, voice and text modes, and how to save real progress to the learner's own repo.
- [VOICE-MODE-GUIDE.md](VOICE-MODE-GUIDE.md) — the voice and text mode guide, with starter prompts for both modes and the manual log template.
- [CURRICULUM.md](CURRICULUM.md) — chapters, learning objectives, and the practical "ready to move on" threshold.
- [progress-templates/](progress-templates/) — blank `STATE.md`, `PROGRESS.md` and `SESSION_LOG.md` templates. Copy these into `education/` in your own repo; they do not exist in the shared copy.
- [visuals/](visuals/) — infographics and schematic maps for the lessons (see the index in `visuals/README.md`). Reference-only: use the one visual that fits the lesson you are teaching.
- [knowledge/history-fun-facts.md](knowledge/history-fun-facts.md) — history and fun facts tied to chapters, to be used sparingly, only where they advance the lesson's story. Reference-only.
- [AUDIT.md](AUDIT.md) and [audit-template.md](audit-template.md) — how to audit progress. Reference-only: not needed to start, only after several sessions.

## Status language (important)
- **Not recorded** — no reliable evidence of meaningful study yet; this does *not* mean the learner knows nothing.
- **Covered** — discussed/studied previously; recall and application still need checking.
- **Practised** — learner attempted explanations, problems, or exercises.
- **Review** — a known gap, misconception, or uncertainty needs revisiting.
- **Mastered** — demonstrated accurate recall and application across **at least two fresh cases**, including a later follow-up. **Nothing is marked Mastered at creation.**

Statuses can be combined, e.g. `Practised · Review`. Notes from conversations before this tracker are **retrospective**, not a formal WSET assessment.

## Source and scope
Official [WSET Level 3 Award in Wines](https://www.wsetglobal.com/qualifications/wset-level-3-award-in-wines): Unit 1 covers the natural and human production factors behind major still, sparkling and fortified wines; Unit 2 covers systematic tasting and quality evaluation. Assessments include theory (multiple-choice and short written answers) and two blind tastings.

This tracker follows these broad domains: viticulture, winemaking, still-wine regions (Europe and New World), sparkling, fortified, WSET SAT tasting, and exam-style written reasoning. Consult the official current specification for exact examinable detail, not this simplified checklist.

This pack is not affiliated with WSET and does not reproduce WSET exam material.

## How tutoring works here
Read **[AGENTS.md](AGENTS.md)** before facilitating any lesson. The learner wants a **WSET tutor**, not an endless quiz. Give a coherent high-level introduction first — as a story, with a clear narrative thread (a vine through a season, a grape through ripening, a region through its climate and history); ask syllabus-linked questions one at a time; use progressively deeper, connected explanations and examples to fill demonstrated gaps; verify functional understanding and syllabus coverage before advancing. The learner controls when to stop; do not repeatedly offer to end.

**Narrative first, not rote memorisation:** teach mechanisms as a connected story — why something matters, what happens next, how it connects to the wine in the glass. Diagnostics test understanding of the story and its causes, not recall of a list. A fact earns its place only if it helps explain a wine style, quality or price. History and fun facts serve the story; use at most 1–2 per session, only where they advance it.

## Default lesson sequence
1. **Orient:** Introduce the subject coherently, with core science, why it matters for wine, WSET scope, and concrete examples (in voice mode, often 1–3 spoken minutes; in text mode, a short sequence of messages telling the same story in order).
2. **Diagnose:** Ask a few purposeful questions, one at a time, to identify what is already understood and what is missing.
3. **Teach:** Provide progressively deeper, connected explanations and examples based on the learner's actual responses; do not endlessly repeat the same question.
4. **Verify:** Check that each important syllabus subtopic was covered and is functionally understood before moving on. Record gaps for spaced review; mastery is a separate, higher standard.
5. **Advance:** Tutor chooses the next syllabus topic without repeatedly asking whether to stop. Learner may interrupt or redirect at any time.

## Background curriculum steward (any agent with repo access)

**Role:** a second, independent authority on the **quality and completeness of the WSET Level 3 learning plan**, not the live conversational tutor. Its job is to maintain and improve the curriculum *between* lessons so the tutor can teach from a prepared, coherent plan rather than improvising the syllabus. Any agent with repo access can fill this role.

**Operating mandate:**
1. **Audit coverage:** Compare `CURRICULUM.md`, `PROGRESS.md`, `STATE.md` and `SESSION_LOG.md` against the current official WSET Level 3 specification. Identify missing learning objectives, weak sequencing, repetition, and factual errors. Cite authoritative sources when adding substantive claims.
2. **Develop lesson plans:** Expand each upcoming subject into a ready-to-teach outline: a high-level introduction; essential causal mechanisms; regional/wine examples; a small set of diagnostic questions asked one at a time; deeper explanations keyed to likely misunderstandings; and a functional-understanding checkpoint. Prepare material in the repository, not as unsolicited live lessons.
3. **Assess evidence honestly:** Read the learner's actual recorded answers and distinguish *introduced*, *covered*, *demonstrated understanding*, *needs review*, and *mastered*. Identify knowledge gaps and propose targeted follow-ups. Never fabricate responses, grades, confidence, or mastery.
4. **Maintain progression:** Ensure each WSET-relevant subtopic is introduced and understood at a functional level before recommending advancement. Preserve spaced-repetition items and unresolved questions. Prioritize causal reasoning (conditions → vine/grape → wine style, quality, price), not rote one-liners.
5. **Continuously improve:** Review new session entries, refine lesson sequence and examples, add useful content, flag incorrect teaching or confusing questions, and leave clear next-session instructions so the live tutor does not have to design the lesson on the fly.

**Collaboration boundaries:**
- The steward may edit curriculum and lesson-preparation material, with traceable commits, **only in the learner's own copy and only when configured and authorized**. This README does not itself start or schedule any agent.
- Treat `SESSION_LOG.md` as an evidence record: preserve actual learner statements and label inference clearly. Do not silently rewrite historical evidence.
- Coordinate through `STATE.md` and `PROGRESS.md`; read fresh versions before writing and avoid overwriting concurrent live-tutor updates.
- Keep the learner's preferred live format: **cohesive introduction → several diagnostic questions one at a time → progressively deeper explanation/examples → coverage and understanding check → next subject**. Do not convert lessons into nonstop quizzes or demand expert mastery of every minor detail.
- Flag uncertainty and disagreements with sources. The live tutor remains responsible for the real-time conversation; the steward provides review, prepared material and an independent quality check.
- A useful steward review should leave: (a) coverage gaps found, (b) concrete content or sequencing changes made, (c) learner understanding still unverified, and (d) a ready-to-use next lesson.

## Study workflow (in the learner's own copy)
1. Read `STATE.md` and the relevant row of `PROGRESS.md` before choosing the next question.
2. Study a topic, then ask for a concise **why/how** explanation or compare two regions in WSET Level 3 short-answer style.
3. Record the learner's *actual response*, corrections, and confidence in `SESSION_LOG.md`.
4. Update evidence and status in `PROGRESS.md`, and update `STATE.md` last. **Save to the learner's own repo** when accessible and confirm whether saving succeeded; if the agent cannot write, give the learner a copyable log entry.
5. Prefer one question at a time, no premature answer reveal; use spaced review of weak topics.

## Preferences to respect
- Direct WSET Level 3 preparation is the goal; some learners arrive without Level 2 and may need the Level 3 Online Entry Test — check the learner's own entry route, do not assume one.
- Approximately **20 minutes of evening review** is a common preference, with tasting practice on weekends; the learner alone decides when a session ends.
- Concrete examples, wine comparisons, and clear distinctions between WSET terminology and personal/critic descriptors.
- Prior tasting experience helps but does **not** automatically count as mastery of theory or the WSET SAT.

## Mandatory uninterrupted tutoring
The learner alone decides when the lesson ends. **Never stop, suggest stopping, say 'that's enough for today' or 'next time', offer a closing summary, or ask whether to continue unless the learner explicitly asks to stop or pause.** A 20-minute study preference, completed subtopic, successful answer, checkpoint, or lesson boundary is NOT permission to end. After answering or assessing, proceed immediately with the next relevant explanation or one diagnostic question; wait for the answer, then continue. This rule overrides any contradictory pacing, session-end, or handoff guidance elsewhere.
