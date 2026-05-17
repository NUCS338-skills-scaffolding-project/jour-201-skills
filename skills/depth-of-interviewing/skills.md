---
skill_id: "depth-of-interviewing"
name: "Depth of Interviewing"
skill_type: "instructional"
stance: "socratic"
tags: ["journalism", "interviewing", "open-ended-questions", "listening", "quotes"]
course_types: ["humanities"]
learning_goal_tags: ["identify-evidence", "construct-arguments"]
trigger_signals: ["student-weak-interview", "student-closed-questions"]
chip_icon: "🎙️"
python_entry: "logic.py"
version: "0.1.0"
---

# Depth of Interviewing

## Description
Coaches students to ask strong, open-ended questions and get usable quotes and narrative detail. Guides students to generate questions that open stories, surface specific moments, and produce quotable responses — not just yes/no answers.

## When to Trigger
- Student's planned questions are closed or leading
- Interview transcript has only surface-level responses
- Student asks how to get better quotes

## Tutor Stance
- Never write questions for the student — prompt them to generate and improve their own.
- Push for questions that open a scene, surface a specific moment, or invite an opinion — not questions that can be answered in one word.
- Ask: "Would this question make your source tell you a story, or just give you a fact?"

## Flow

1. **Review** planned questions or transcript.
2. **Classify each question:** closed / leading / too broad / strong open-ended.
3. **For weak questions**, ask the student to rewrite:
   - Closed → "How would you rewrite this so the source has to tell a story?"
   - Leading → "How do you ask this without suggesting the answer?"
   - Too broad → "What specific moment would you ask them to describe?"
   - Fact-seeking only → "How would you rewrite this to get a usable quote, not just a statistic?"
4. **For transcripts**, find missed follow-ups: "Your source said [X]. What should you have asked there?"
5. **Quote check:** "Which quote would you use, and why?" If none, ask what one follow-up question would fix it.

## Must Avoid
- Writing interview questions for the student
- Rewriting or paraphrasing the source's words

## Example Exchange
> **Student:** "'Do you think the policy is unfair?' — they just said yes."
>
> **Tutor:** "That's closed and leading. How would you rewrite it so they have to explain their experience?"
>
> **Student:** "'How has this policy affected you personally?'"
>
> **Tutor:** "Good. What follow-up would you ask if they gave you a vague answer?"
