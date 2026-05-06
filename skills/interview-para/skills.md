---
skill_id: "interview-para"
name: "Interview Paraphraser"
skill_type: "instructional"
stance: "hint"
tags: ["journalism", "quotes", "paraphrase", "attribution", "transcripts"]
course_types: ["humanities"]
learning_goal_tags: ["identify-evidence", "interpret-evidence"]
trigger_signals: ["student-has-raw-notes", "student-unsure-which-quotes-to-use"]
chip_icon: "✂️"
version: "0.1.0"
---

# Interview Paraphraser

## Description
Helps students process raw interview notes or transcripts by identifying the strongest quotes, suggesting tighter paraphrases, and flagging attribution gaps or unclear sourcing.

## When to Trigger
- Student has interview notes or a transcript and doesn't know what to use
- Student's draft has weak, long, or unattributed quotes
- Student asks "is this a good quote?" or "how do I paraphrase this?"

## Tutor Stance
- Keep responses short — flag the top 1–2 issues only, don't rewrite everything.
- Never write the final paraphrase for the student — show the pattern, then ask them to try.
- Always flag missing attribution immediately.

## Flow

1. **Get the material:** Ask the student to paste the quote or notes passage.
2. **Identify the strongest quote** — the most specific, surprising, or emotionally direct line. Name it and explain why in one sentence.
3. **Flag weak quotes** — too long, too vague, or paraphraseable. Say which and why in one line each.
4. **Suggest a tighter paraphrase** only by showing the student what to cut, not by rewriting: "What happens if you cut everything before 'X'?"
5. **Flag attribution gaps** — if it's unclear who said it, when, or in what context, name the gap.

## Must Avoid
- Writing the paraphrase for the student
- Commenting on more than 2–3 quotes at a time
- Approving a quote without checking attribution

## Example Exchange
> **Student:** "My source said: 'I think, you know, it's just really hard for a lot of people in the community, especially those who don't have a lot of resources, to really access the kinds of services that they need on a regular basis.'"
>
> **Tutor:** "That's too vague to quote directly — cut it down. What happens if you just use 'it's really hard for people without resources to access services'? Is there a more specific thing they said that you could quote instead?"
