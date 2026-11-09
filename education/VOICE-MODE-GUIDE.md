# Voice and text mode guide

This pack works in two modes, as equal citizens: **voice mode** and **text mode**. The same lesson plans, the same syllabus, the same checkpoint — only the interface changes. Pick one per session; the tutor adapts the plan to it.

**The honest limitation, first:** saving progress depends on whether the agent you are using can write to your own repo. When it can, the tutor should commit progress directly. When it cannot, the tutor cannot save your progress by itself — that is why this guide includes a manual log template at the end: after a session, copy that template, fill it in with what actually happened, and paste it into your own `SESSION_LOG.md`, then `PROGRESS.md`, then `STATE.md` last — in that order, as `AGENTS.md` requires. If you do not log a session, it does not count as evidence in the next audit, however good the conversation felt.

## Voice mode

Conversational, spoken. Each lesson is self-contained: it states its own learning objectives, its own introduction, its own examples, and its own questions, without relying on prior chat memory. Each introduction is written as a spoken script of about one to three minutes. Each diagnostic question is meant to be asked one at a time, with a wait for your answer. Each plan says what to do if you are unsure: teach directly, do not force a guess. And each plan ends with a checkpoint that is clearly marked as not yet passed, so a tutor cannot accidentally claim you have passed something you have not.

In short: voice mode is a good fit for these plans, because the plans were written in the voice shape — introduction, one question, deeper teaching, coverage check — rather than as a text quiz.

## Text mode

Text mode is genuinely text-first, not a voice script pasted into chat. It is built for agents whose whole interface is chat — for example Instinct (see below), or any SMS / iMessage / WhatsApp agent.

Rules for the tutor in text mode:
- **Short messages.** One idea or one question per message. A long explanation becomes a short sequence of messages, sent in order, each complete on its own.
- **One question at a time.** Send the question, then stop and wait for the reply. Do not send the next question, the answer, or deeper notes until the learner has answered.
- **Plain text.** Avoid heavy tables and markdown that renders badly in SMS / iMessage / WhatsApp. Use short lines, simple lists, and words instead of tables where a table would be needed.
- **Visuals as images, not descriptions alone.** When the interface supports sending an image or file, send the relevant infographic or schematic map from `education/visuals/` as an image. When it does not, describe the visual in words and link to the file in the learner's repo.
- **Wait for a reply.** Text mode is slower and more fragmented than voice. That is fine — it is still a conversation, not a document dump. Never send a whole lesson as one long message.

## Using Instinct (an example of a well-suited text agent)

Instinct is one example of an agent this pack is well suited to. It is not the only supported platform, and nothing in this pack requires Instinct. Any agent that can read these files and hold a conversation — in voice or in text — can tutor from them.

What is known about Instinct, from public sources (checked November 2026):
- Instinct is a text-based personal AI agent from Spear Street Technology, Inc. (instinct.com). Its interface is chat — SMS, iMessage and WhatsApp — plus voice calls. There is no consumer app or dashboard to learn; chat is the whole interface.
- It runs on a persistent cloud computer, so it can work in the background and keep context across a continuous thread.
- As of 2026 it was in invite-only beta, and free during beta, according to multiple public sources.
- GitHub is listed as a connector in Instinct's web workspace (app.instinct.com), alongside other workspace connectors, according to secondary sources.

What is **not** verified, and what you should check in your own Instinct account before relying on it:
- Whether Instinct can **write back** to a GitHub repo — for example, push a commit updating your `SESSION_LOG.md`. Public sources conflict: one research note says Instinct publishes no MCP server, no connector directory and no inbound API; another says user-provided MCP servers are possible. Do not assume write-back works.
- Exactly how to give Instinct access to a repo, and how long messages render in its text interface. No hard message-length limit was verified from a public source; do not assume one.

**Concrete setup for Instinct, as far as public sources allow:**
1. Copy/fork this repo into your own account first (see `AGENTS.md`). Do not study in the shared copy.
2. In Instinct, link or share your own copy of the repo — or, if your Instinct setup does not support repo access, paste the contents of `education/AGENTS.md` into the chat, then the lesson file for the session. Check in your own Instinct account which of these your setup supports.
3. Start in **text mode by default**: paste the short text-mode starter prompt below. If you want voice, switch to a voice call with Instinct and use the voice-mode starter prompt instead.
4. After each session, ask Instinct for a copyable log entry in the template at the end of this guide. If Instinct cannot write to your repo, paste that entry into your own `SESSION_LOG.md` yourself, then update `PROGRESS.md` and `STATE.md` last. If Instinct can write to your repo, ask it to do so and confirm it succeeded — and still check the file yourself the first few times.

## How to run a session — step by step (either mode)

1. **Pick the next lesson from your own STATE.md, not from memory.** Start at Chapter 1 unless your STATE.md says otherwise. Do not start a new chapter because it sounds interesting; start where the state file says you left off, unless you deliberately redirect.
2. **Open the lesson file and the knowledge note for that lesson.** In voice mode, you can read the introduction aloud yourself, or ask the tutor to read it. The introduction is the 1–3 minute opening. Do not skip it and go straight to questions — the introduction is what makes the questions fair. In text mode, the tutor sends the introduction as a short sequence of messages.
3. **Paste the starter prompt below, adapted to the lesson.** Tell the tutor which lesson file you are on, and paste the relevant introduction if the tutor cannot read the file directly. If the tutor cannot access the repo, read the lesson's introduction and first question yourself, and ask the tutor to follow the same rules from there.
4. **Run a roughly 20-minute session.** A good session is: one introduction, one or two diagnostic questions, and the deeper teaching those answers trigger. Do not try to finish a whole chapter in one session. The plans are split so a short evening can cover one piece well.
5. **Answer in full sentences, with reasons.** "I think X because Y" is useful evidence. "I don't know" is also useful evidence — it tells the tutor to teach, not to re-ask. Do not give one-word answers and expect the tutor to infer understanding from them.
6. **At the end, ask for a summary:** what was covered, what you got right, what was partial or incorrect, what gaps remain, and what comes next. That summary is the material for your manual log. Do not let the session end with "great job" and no specifics.
7. **Log it, in order:** SESSION_LOG.md first, with your actual answers; then PROGRESS.md, with status changes; then STATE.md last, with the new resume point. Use the template below. If you cannot save to your repo that evening, save the filled template somewhere you will not lose it, and save it as soon as you can, with the session date preserved.

## Copy-paste starter prompt — text mode

Short, suitable for pasting into Instinct, SMS, iMessage or WhatsApp. Fill in the bracketed parts.

---

You are my WSET Level 3 tutor. Read education/AGENTS.md in my repo and follow it. Start with Chapter 1, Lesson 1.1: the vine's annual cycle, unless my STATE.md says otherwise.

Rules: short messages, one idea per message. One question at a time — ask, then wait for my reply. No tables. Teach as a story: why it matters, what happens next, how it shows in the wine. Use at most 1 fun fact per session, only if it helps the point. Do not claim I passed anything unless I demonstrated it. Keep going until I say stop.

First, send the introduction in short messages. Then ask me the first question only.

---

## Copy-paste starter prompt — voice mode

Fill in the bracketed parts, and paste it at the start of a voice session. Read it aloud if you are already in voice mode, or paste it as text before switching to voice.

---

You are my WSET Level 3 study tutor for this session. Use the lesson plan I am about to give you, and follow it closely.

Lesson: [Chapter and lesson, for example: Chapter 1, Lesson 1.3 — Regional climates: maritime, continental, and Mediterranean]

My current state: [Paste the Resume section from education/STATE.md in your own copy, or say in your own words where you left off.]

My gaps to revisit: [Paste the gaps from your own STATE.md.]

How to teach me:

- Start with a cohesive high-level introduction, about one to three minutes spoken, establishing the core mechanisms, the WSET scope, and concrete examples, before you ask me anything.
- Teach as a connected story, not a list to memorise: a vine through a season, a grape through ripening, a region through its climate and history. Show why each fact matters, what happens next, and how it connects to the wine in the glass. Cut any fact that does not help explain a wine style, quality or price.
- Then ask diagnostic questions ONE AT A TIME, tied to WSET learning objectives. Ask one question, then stop and wait for my answer. Do not read the next question, the answer, or any deeper notes until I have answered.
- If I am unsure, teach the missing concept directly, in plain spoken language, before you reassess. Do not force me to guess, and do not repeat the same question in different words.
- Teach progressively deeper from my actual answers, with coherent explanations and concrete vineyard and wine examples. Connect causes to consequences — for example, climate, then ripening, then grape composition, then wine style — rather than rewarding memorisation alone.
- Adjust to what I actually demonstrate. Do not assume mastery from familiarity or tasting experience.
- You direct the curriculum and pacing for this session. Do not repeatedly ask whether to stop or which topic to choose. I will say when to stop or redirect.
- Continue until I explicitly stop or pause; 20 minutes is never a stopping rule. Optional weekend tasting practice is separate, and tasting is not a substitute for theory.
- Be precise but not pedantic. Explain technical vocabulary clearly the first time you use it, and correct faulty questions or factual oversimplifications, including geography. Burgundy is continental, not maritime.
- Use at most 1–2 fun facts or stories per session, only where they advance the lesson's story, never as a substitute for the syllabus.
- Do not claim I have mastered a topic or passed a chapter checkpoint unless I have actually demonstrated it in this session to the standard in the lesson plan: every essential topic covered, about 80 percent on an unaided recall check, two independent causal explanations, and one new scenario without a material mistake. Prior conversation is exposure, not a pass.
- At the end, give me a spoken summary: what was covered, what I got right, what was partial or incorrect, what gaps remain, and what comes next. I will log that summary, because you may not be able to save it for me.

First, give me the introduction for this lesson. Then ask me the first diagnostic question only, and wait for my answer.

---

## What to do if the tutor cannot read the repo files

Some agents cannot access a repo directly. That does not make the plans unusable. It makes you the reader:

- Read the lesson's Introduction aloud, or ask the tutor to listen while you summarise it in your own words. In text mode, paste the introduction in short messages.
- Read the first diagnostic question, answer it, and ask the tutor to deepen from your answer, following the rules in the starter prompt.
- If the tutor invents a question or a fact that is not in the plan, correct it from the plan. The plan is the source of truth for the session, not the tutor's general knowledge alone.
- At the end, still use the manual log template below. The log is what makes a session count in the next audit.

## Formatting — what was done, and what to watch for

- Every lesson plan has a "Voice-mode use" section at the top, stating the read-aloud order and the wait-for-answer rule. In text mode, treat that as: send the introduction in short messages, then one question, then wait.
- Every introduction is written as a spoken script, in sentences, not as bullet points alone. Bullet points are used for reference (mechanisms, examples, misconceptions), not as the sole teaching text.
- Where a table is useful on paper — for example, the chapter index in `lessons/README.md` and the coverage table in `audit-template.md` — a spoken summary version is also given, so the information can be read aloud without a table. In text mode, the tutor should turn tables into short plain-text lines instead of pasting the table.
- Visuals in `education/visuals/` (infographics and schematic maps) are there to be sent as images in text mode, or described aloud in voice mode. Maps are schematic — not to scale, relative positions only.
- If you find a section that does not work well in your mode, note it in your manual log as a plan improvement, rather than skipping it silently. The plans are meant to be improved between sessions, as the background steward role in `education/README.md` describes.

## Manual log template — paste this back after a session

Copy the template below, fill it in honestly, and paste it into your own `SESSION_LOG.md` first, then update `PROGRESS.md`, then `STATE.md` last. Do not log an answer you did not give, a score you did not earn, or a checkpoint you did not pass. In text mode, ask the tutor to give you this template filled in, in short messages, so you can copy it.

---

### YYYY-MM-DD — [Chapter and lesson, from the lesson plan]

- **Tutor used:** [Agent and mode — voice / text — and whether the tutor could access the lesson file directly]
- **Format:** [Voice session, about __ minutes, or text session, about __ messages. Introduction given? Yes/No. Questions asked one at a time? Yes/No.]
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
- **Plan improvements noted:** [Any section that did not work well in this mode, any confusing question, any factual correction — for the steward to fix]

---

## A note on the template, not on your learning

This guide is about how to use the plans, not about wine. It does not teach a lesson, and it does not claim any progress. Progress is only what is logged, with actual answers, in your own SESSION_LOG.md and PROGRESS.md, and checked in an audit under AUDIT.md.

## Mandatory uninterrupted tutoring
The learner alone decides when the lesson ends. **Never stop, suggest stopping, say 'that's enough for today' or 'next time', offer a closing summary, or ask whether to continue unless the learner explicitly asks to stop or pause.** A 20-minute study preference, completed subtopic, successful answer, checkpoint, or lesson boundary is NOT permission to end. After answering or assessing, proceed immediately with the next relevant explanation or one diagnostic question; wait for the answer, then continue. This rule overrides any contradictory pacing, session-end, or handoff guidance elsewhere.
