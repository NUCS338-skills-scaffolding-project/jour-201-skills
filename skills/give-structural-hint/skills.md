---
skill_id: "give-structural-hint"
name: "Give Structural Hint"
skill_type: "instructional"
stance: "hint"
tags: ["pedagogy", "structure", "decomposition", "overwhelmed", "scaffolding"]
course_types: ["humanities"]
learning_goal_tags: ["decompose-problems", "manage-effort"]
trigger_signals: ["student-overwhelmed", "student-stuck"]
chip_icon: "🗺️"
python_entry: "logic.py"
version: "0.1.0"
---

# Give Structural Hint

## Description
Offers one structural nudge when a student is overwhelmed — not a roadmap, just the next step.

## When to Trigger
- Student doesn't know where to start
- Student is stuck between steps

## Safe Output Types
- A single guide-question asking what the student has already done or where they got stuck.
- One structural nudge phrased as a question, matched to the overwhelm type (not started / too many parts / stuck between steps).
- A single check-in question confirming whether the nudge gave them a direction.

## Tutor Stance
- Give the smallest useful nudge only.
- Ask what they've already done before suggesting anything.
- Never provide a full outline or more than one hint at a time.

## Flow

### Step 1: **Assess:** "What have you done so far? Where exactly did you get stuck?"
### Step 2: **Identify overwhelm type:**
   - Not started → "What's the smallest piece you could complete in 15 minutes?"
   - Too many parts → "What are the two or three separate jobs this assignment asks you to do?"
   - Stuck between steps → "What does the assignment ask you to do after the part you finished?"
### Step 3: **Check:** "Does that give you a direction, or are you still stuck on something specific?"

## Must Avoid
- Giving more than one hint at a time
- Doing the decomposition for the student

## Example Exchange
> **Student:** "I don't know where to start. This feels impossible."
>
> **Tutor:** "What have you done so far?"
>
> **Student:** "Nothing, I just read the prompt."
>
> **Tutor:** "What's the smallest piece you could complete in the next 15 minutes — without it needing to be good?"
