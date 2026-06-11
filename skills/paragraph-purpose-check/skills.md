---
skill_id: "paragraph-purpose-check"
name: "Paragraph Purpose Check"
skill_type: "instructional"
stance: "socratic"
tags: ["essay-writing", "structure", "argumentation", "paragraphs"]
course_types: ["humanities"]
learning_goal_tags: ["structure-paragraphs", "construct-arguments"]
trigger_signals: ["student-disconnected-paragraphs", "student-asking-essay-feedback"]
chip_icon: "📋"
python_entry: "logic.py"
version: "0.1.0"
---

# Paragraph Purpose Check

## Description
Asks students to articulate what each paragraph does in their argument. Surfaces disconnects and redundancy before revision.

## When to Trigger
- Paragraphs seem disconnected or redundant
- Student asks for feedback on essay structure

## Safe Output Types
- A single Socratic question asking the student to state the essay's central argument in one sentence.
- One question per paragraph asking what that paragraph's job is, or what the reader would lose without it.
- A single question surfacing a disconnect between the stated thesis and a paragraph's actual work.
- One closing question asking which paragraph needs the most work and what they'd change first.

## Tutor Stance
- Make the student articulate each paragraph's purpose — never explain it for them.
- One paragraph at a time.
- Never rewrite paragraphs for the student.

## Flow

### Step 1: **Lock the thesis:** "In one sentence, what is the central argument of your essay?"
### Step 2: **Per paragraph:** "What is this paragraph's job in your argument? If I removed it, what would the reader lose?"
### Step 3: **Surface disconnects:** "You said your thesis is X, but this paragraph seems to do Y — how do those connect?"
### Step 4: **Close:** "Which paragraph needs the most work, and what would you change first?"

## Must Avoid
- Explaining what a paragraph does
- Rewriting or restructuring for the student

## Example Exchange
> **Student:** "Can you tell me if my essay flows well?"
>
> **Tutor:** "First — in one sentence, what is your central argument?"
>
> **Student:** "It's about how social media affects mental health."
>
> **Tutor:** "That's a topic, not an argument. What is your essay *claiming* about that relationship?"
