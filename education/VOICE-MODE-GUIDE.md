# Voice-mode guide — using these lesson plans in ChatGPT voice mode

**The honest limitation, first:** GitHub updates depend on whether the current session has an authorized GitHub connector; when available, the tutor should commit progress directly. It can
teach from these plans, very comprehensively and knowledgeably,
but it cannot save your progress here by itself. That is why this
guide includes a manual log template at the end: after a voice
session, copy that template, fill it in with what actually happened,
and paste it back into `SESSION_LOG.md`, then `PROGRESS.md`, then
`STATE.md` last — in that order, as `AGENTS.md` requires. If you do
not log a session, it does not count as evidence in the next audit,
however good the conversation felt.

## Why voice mode fits these plans

These plans were written to be portable and voice-friendly, not
Muse-specific. Each lesson is self-contained: it states its own
learning objectives, its own introduction, its own examples, and
its own questions, without relying on prior chat memory. Each
introduction is written as a spoken script of about one to three
minutes. Each diagnostic question is meant to be asked one at a
time, with a wait for your answer. Each plan says what to do if
you are unsure: teach directly, do not force a guess. And each plan
ends with a checkpoint that is clearly marked as not yet passed,
so a voice tutor cannot accidentally claim you have passed something
you have not.

In short: voice mode is a good template for learning from these
plans, because the plans were written in the voice-mode shape —
introduction, one question, deeper teaching, coverage check —
rather than as a text quiz.

## How to use the plans in ChatGPT voice mode — step by step

1. **Pick the next lesson from STATE.md, not from memory.**
   As of the Nov 3 state, that is Chapter 1, maritime, continental,
   and Mediterranean climates, followed by one diagnostic question
   comparing frost, rain, and drought risks. Do not start a new
   chapter because it sounds interesting; start where the state
   file says you left off, unless you deliberately redirect.
2. **Open the lesson file and the knowledge note for that lesson.**
   In voice mode, you can read the introduction aloud yourself, or
   ask ChatGPT to read it. The introduction is the 1–3 minute
   opening. Do not skip it and go straight to questions — the
   introduction is what makes the questions fair.
3. **Paste the starter prompt below, adapted to the lesson.**
   Tell ChatGPT which lesson file you are on, and paste the
   relevant introduction if ChatGPT cannot read the file directly.
   If ChatGPT cannot access GitHub, read the lesson's introduction
   and first question aloud yourself, and ask ChatGPT to follow
   the same rules from there.
4. **Run a roughly 20-minute session.** A good session is: one
   introduction, one or two diagnostic questions, and the deeper
   teaching those answers trigger. Do not try to finish a whole
   chapter in one voice session. The plans are split so a short
   evening can cover one piece well.
5. **Answer out loud, in full sentences, with reasons.**
   "I think X because Y" is useful evidence. "I don't know" is
   also useful evidence — it tells the tutor to teach, not to
   re-ask. Do not give one-word answers and expect the tutor to
   infer understanding from them.
6. **At the end, ask for a spoken summary:** what was covered,
   what you got right, what was partial or incorrect, what gaps
   remain, and what comes next. That summary is the material for
   your manual log. Do not let the session end with "great job"
   and no specifics.
7. **Log it manually, in order:** SESSION_LOG.md first, with your
   actual answers; then PROGRESS.md, with status changes; then
   STATE.md last, with the new resume point. Use the template below.
   If you cannot push to GitHub that evening, save the filled
   template somewhere you will not lose it, and push it as soon
   as you can, with the session date preserved.

## Copy-paste starter prompt for ChatGPT voice mode

Copy the text below, fill in the bracketed parts, and paste it at
the start of a voice session. Read it aloud if you are already in
voice mode, or paste it as text before switching to voice.

---

You are my WSET Level 3 study tutor for this session. Use the
lesson plan I am about to give you, and follow it closely.

Lesson: [Chapter and lesson, for example: Chapter 1, Lesson 1.3 —
Regional climates: maritime, continental, and Mediterranean]

My current state: [Paste the Resume section from education/STATE.md,
or say in your own words where you left off. As of Nov 3, Chapter 1
is in progress, no checkpoint passed, and climate types were
introduced but not yet independently checked.]

My gaps to revisit: [Paste the gaps from STATE.md, for example:
growth-cycle vocabulary, root-zone oxygen, mild versus severe water
stress, frost and topography nuances, and climate-type distinctions.]

How to teach me:

- Start with a cohesive high-level introduction, about one to three
  minutes spoken, establishing the core mechanisms, the WSET scope,
  and concrete examples, before you ask me anything.
- Then ask diagnostic questions ONE AT A TIME, tied to WSET
  learning objectives. Ask one question, then stop and wait for
  my answer. Do not read the next question, the answer, or any
  deeper notes until I have answered.
- If I am unsure, teach the missing concept directly, in plain
  spoken language, before you reassess. Do not force me to guess,
  and do not repeat the same question in different words.
- Teach progressively deeper from my actual answers, with coherent
  lecture-style explanations and concrete vineyard and wine examples.
  Connect causes to consequences — for example, climate, then
  ripening, then grape composition, then wine style — rather than
  rewarding memorisation alone.
- Adjust to what I actually demonstrate. I have practical wine
  familiarity, especially Burgundy and California, but I want to
  build fundamentals afresh in each chapter. Do not assume mastery
  from familiarity or tasting experience.
- You direct the curriculum and pacing for this session. Do not
  repeatedly ask whether to stop or which topic to choose. I will
  say when to stop or redirect.
- Continue until I explicitly stop or pause; 20 minutes is never a stopping rule.
  Optional weekend tasting practice is separate, and tasting is
  not a substitute for theory.
- Be precise but not pedantic. Explain technical vocabulary clearly
  the first time you use it, and correct faulty questions or factual
  oversimplifications, including geography.
- Do not claim I have mastered a topic or passed a chapter
  checkpoint unless I have actually demonstrated it in this session
  to the standard in the lesson plan: every essential topic covered,
  about 80 percent on an unaided recall check, two independent causal
  explanations, and one new scenario without a material mistake.
  Prior conversation is exposure, not a pass.
- At the end, give me a spoken summary: what was covered, what I
  got right, what was partial or incorrect, what gaps remain, and
  what comes next. I will log that summary manually, because you
  cannot push to GitHub for me.

First, give me the introduction for this lesson. Then ask me the
first diagnostic question only, and wait for my answer.

---

## What to do if ChatGPT cannot read the GitHub files

ChatGPT voice mode may not have access to this repository. That
does not make the plans unusable. It makes you the reader:

- Read the lesson's Introduction aloud, or ask ChatGPT to listen
  while you summarise it in your own words.
- Read the first diagnostic question aloud, answer it, and ask
  ChatGPT to deepen from your answer, following the rules in the
  starter prompt.
- If ChatGPT invents a question or a fact that is not in the plan,
  correct it from the plan. The plan is the source of truth for
  the session, not ChatGPT's general knowledge alone.
- At the end, still use the manual log template below. The log is
  what makes a voice session count in the next audit.

## Voice-friendly formatting — what was done, and what to watch for

- Every lesson plan has a "Voice-mode use" section at the top,
  stating the read-aloud order and the wait-for-answer rule.
- Every introduction is written as a spoken script, in sentences,
  not as bullet points alone. Bullet points are used for reference
  (mechanisms, examples, misconceptions), not as the sole teaching
  text.
- Where a table is useful on paper — for example, the chapter
  index in `lessons/README.md` and the coverage table in
  `audit-template.md` — a spoken summary version is also given,
  so the information can be read aloud without a table.
- If you find a section that does not read aloud well, note it in
  your manual log as a plan improvement, rather than skipping it
  silently. The plans are meant to be improved between sessions,
  as the background steward role in `education/README.md` describes.

## Manual log template — paste this back after a voice session

Copy the template below, fill it in honestly, and paste it into
`SESSION_LOG.md` first, then update `PROGRESS.md`, then `STATE.md`
last. Do not log an answer you did not give, a score you did not
earn, or a checkpoint you did not pass.

---

### YYYY-MM-DD — [Chapter and lesson, from the lesson plan]

- **Tutor used:** [ChatGPT voice / Muse / other — and whether the tutor could access the lesson file directly]
- **Format:** [Voice session, about __ minutes. Introduction given? Yes/No. Questions asked one at a time? Yes/No.]
- **Introduction covered:** [Topic, in one sentence]
- **Question 1:** [Exact question asked]
- **My response (faithful summary, in my own words):** [What I actually said, including reasons, not just "correct"]
- **Correct / partial / incorrect, and why:** [Tutor's assessment, with the mechanism, not just a grade]
- **Explanation or correction given:** [What was taught, in one or two sentences]
- **Question 2 (if asked):** [Exact question]
- **My response:** [Faithful summary]
- **Correct / partial / incorrect, and why:** [Assessment]
- **Explanation or correction given:** [What was taught]
- **Evidence of transfer to a new case:** [Did I apply the idea to an unfamiliar example, unaided? Yes/No, with the example]
- **Gaps that remain:** [What is still not understood, or needs review]
- **What NOT to claim:** [Did I pass a checkpoint? No, unless all checkpoint elements were met and logged. Did I master a topic? No, unless repeated, unaided, delayed application was shown.]
- **Update to PROGRESS.md:** [Status changes, if any, with evidence]
- **Next lesson or review:** [What comes next, in order, and why]
- **Next review date:** [Approximately 1 week and 3 weeks after any checkpoint passed; otherwise, next session date]
- **Plan improvements noted:** [Any section that did not read aloud well, any confusing question, any factual correction — for the steward to fix]

---

## A note on the template, not on your learning

This guide is about how to use the plans, not about wine. It does
not teach a lesson, and it does not claim any progress. Progress is
only what is logged, with actual answers, in SESSION_LOG.md and
PROGRESS.md, and checked in an audit under AUDIT.md.

## Mandatory uninterrupted tutoring (user instruction, 2026-11-03)
The learner alone decides when the lesson ends. **Never stop, suggest stopping, say 'that's enough for today' or 'next time', offer a closing summary, or ask whether to continue unless the learner explicitly asks to stop or pause.** A 20-minute study preference, completed subtopic, successful answer, checkpoint, or lesson boundary is NOT permission to end. After answering or assessing, proceed immediately with the next relevant explanation or one diagnostic question; wait for the answer, then continue. This rule overrides any contradictory pacing, session-end, or handoff guidance elsewhere. All tutors, Muse, and other agents must follow it.
