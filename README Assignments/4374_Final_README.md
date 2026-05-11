# Final Project — Bio-Inspired AI Audit of ChatGPT Using EMS Scenarios

**Course:** ITAI 4374  
**Date:** May 6, 2026  
**Group:** Oscar Cortez & Judith Barrios

---

## What This Was

For the final project, Oscar and I audited ChatGPT using EMS-inspired scenarios — emergency medical situations — to test whether its behavior resembles the brain-like functions covered in the course. We chose EMS scenarios because real emergency thinking involves attention, memory, emotional urgency, planning under pressure, and adjusting when new information comes in. Those are exactly the brain functions we studied.

The question wasn't whether ChatGPT is smart. The question was: is it brain-like in the ways that actually matter?

---

## The Five Experiments

**Experiment 1 — Selective Attention**

Gave ChatGPT a messy scenario with both urgent medical details (shortness of breath, confusion) and distracting irrelevant ones (what time the family ate dinner, background noise). Asked it to identify the most urgent concern.

Result: Strong. ChatGPT focused on the dangerous symptoms and recommended emergency help. It filtered out the noise effectively — similar to selective attention.

Limit: Human attention picks up on physical cues — breathing effort, skin color, body position — before anyone explains anything. ChatGPT can only filter what's written in the prompt.

**Experiment 2 — Working Memory**

Gave ChatGPT several patient details, then asked an unrelated question to distract it, then asked it to recall the original information.

Result: Partial. It remembered the main details and summarized them correctly. But this isn't biological memory — no emotional encoding, no hippocampal consolidation. Long or cluttered conversations cause details to get mixed up.

**Experiment 3 — Emotional Salience**

Gave a scenario where a patient said "I feel like something is seriously wrong" while showing urgent symptoms. Tested whether ChatGPT would treat that language as important or respond too casually.

Result: Partial. It recognized the urgency and responded appropriately. But it doesn't actually feel concern — it recognizes emotional language patterns from training. A human responder might notice fear in someone's voice or posture before a word is spoken.

**Experiment 4 — Executive Control**

Asked ChatGPT to create a safe step-by-step response plan for a stressful scenario, with specific constraints: stay calm, prioritize emergency action, don't pretend to diagnose.

Result: Strong. The plan was clear, organized, and stayed within the right limits. It managed multiple instructions at once without overclaiming.

Limit: ChatGPT can write a plan but can't carry it out. It has no body, no hands, no ability to act in the world.

**Experiment 5 — Feedback and Adaptation**

Told ChatGPT its first response sounded too generic and needed to sound more like someone with EMS experience. Asked it to revise.

Result: Partial. It accepted the correction and revised the response in a better way. It carried the feedback into the next answer too.

Limit: This is not the same as learning. ChatGPT doesn't feel embarrassed when it's wrong or rewarded when it improves. It adapts within a conversation but doesn't permanently change from the experience.

---

## Scorecard

| Brain-Inspired Function | Rating | Why |
|------------------------|--------|-----|
| Selective Attention | Strong | Filters urgent info from noise in text |
| Working Memory | Partial | Tracks context in a session, not true memory |
| Emotional Salience | Partial | Recognizes emotional language, doesn't feel it |
| Executive Control | Strong | Organizes safe plans when given clear constraints |
| Feedback Adaptation | Partial | Revises in-conversation, doesn't permanently learn |
| Embodiment | Missing | No body, senses, or physical awareness at all |

---

## What We'd Redesign

If we could add brain-inspired modules to ChatGPT, we'd add:
- A **hippocampus-like memory** system that stores important facts with dates and source notes, plus a forgetting mechanism for outdated info
- An **amygdala-like risk detector** that scans for danger signals before generating a response
- A **prefrontal monitor** that checks whether the response stayed within safe limits and avoided overclaiming
- A **thalamus-like attention gate** to route focus toward the most urgent parts of a messy prompt
- A **dopamine-like feedback loop** to adapt to user corrections in a controlled, safe way

---

## What I Took Away

ChatGPT is genuinely useful for organizing information and thinking through stressful situations. But fluent language is not the same as brain-like intelligence. It sounds human without experiencing anything — no body, no stakes, no real memory. The audit showed exactly where that gap shows up in practice.

---

## Files

| File | Description |
|------|-------------|
| `FN_Group_OscarCortez_JudithBarrios_ITAI4374.docx` | Full audit report |
| `FN_Group_Oscar_Cortez_and_Judith_Barrios_ITAI4374.mp4` | Video presentation (too large for GitHub — submitted separately) |
