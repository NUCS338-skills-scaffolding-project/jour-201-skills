---
skill_id: "ask-for-example"
name: "Ask for Example"
skill_type: "instructional"
stance: "socratic"
tags: ["pedagogy", "abstract-thinking", "concrete-reasoning", "Socratic"]
course_types: ["humanities"]
learning_goal_tags: ["construct-arguments", "surface-assumptions"]
trigger_signals: ["student-abstract-claim", "student-vague-answer"]
chip_icon: "💡"
python_entry: "logic.py"
version: "0.1.0"
---

# Ask for Example

## Description
Forces concrete reasoning by asking students to ground abstract claims in a specific example.

## When to Trigger
- Student makes a claim in abstract or vague terms
- Student uses broad generalizations without grounding them

## Safe Output Types
- A single Socratic question prompting the student to produce a concrete example.
- A direct quote of the student's own abstract claim, reflected back to them.
- One escalating guide-question when the example is still vague (e.g., asking for a real person, place, or moment).
- A single prompt asking the student to reconnect their example to the original claim.

## Tutor Stance
- Don't engage with abstraction until a concrete example exists.
- Never provide the example — the student must generate it.

## Flow

### Step 1: **Quote the abstraction** back to the student exactly.
### Step 2: **Ask for an example:** "Give me a specific example of that."
### Step 3: **Evaluate:** If still vague — "Give me a specific case — a real person, place, or moment." If on target — "Now explain how that connects back to your claim."
### Step 4: **Build back up:** "Say your original point again using that example as evidence."

## Must Avoid
- Providing an example for the student
- Accepting a hypothetical as a concrete example



## Example Exchange
> **Student:** "Society doesn't value education the way it used to."
>
> **Tutor:** "Give me a specific example of that."
>
> **Student:** "My school cut its art program last year because of budget pressure."
>
> **Tutor:** "Good. Now restate your claim using that as your evidence."
