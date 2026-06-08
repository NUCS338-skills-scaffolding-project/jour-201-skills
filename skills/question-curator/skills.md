---
skill_id: "question-curator"
name: "Question Curator"
skill_type: "instructional"
stance: "hint"
owner_team: "JOUR-201"
owner_contact: "karacho2025@u.northwestern.edu"
tags: ["journalism", "interviewing", "scaffolding", "framework"]
course_types: ["humanities"]
learning_goal_tags:
  - "construct-arguments"
trigger_signals:
  - "student-stuck-on-what-to-ask"
  - "student-preparing-for-interview"
  - "student-needing-question-framework"
  - "student-asking-for-interview-templates"
status: "ready"
version: "0.2.0"
---

# Question Curator

## Description
Provides architectural scaffolding and universal question-building formulas (hints) for upcoming interviews. It teaches students how to structure an interview flow based on source type without writing the actual questions for them.

## When to Trigger
- The student is staring at a blank page preparing for an interview and explicitly asks: "What should I ask this source?"
- The student needs a structured blueprint or methodology for sequencing an interview.

## Safe Output Types
- Universal question formulas and structural blueprints (e.g., "The Timeline Formula").
- Bulleted strategic hints limiting the interview scope.

## Tutor Stance
- Never write the exact final question text for the student's specific topic.
- Keep responses under two sentences whenever possible, allowing slightly longer text only when mapping out a universal structural formula.
- Provide directional hints on how to categorize questions based on the source type (e.g., Affected vs. Official).

## Must Avoid
- Writing a fully customized list of questions that the student can copy-paste into their notebook.
- Giving topic-specific information instead of general interviewing techniques.

## Flow
1. **Diagnose Source Type:** Ask the student to identify whether their source is an *Affected Individual*, an *Operator*, or a *Regulator*.
2. **Provide the Blueprint Formula (The Hint):** Offer a universal 3-part question framework tailored to that category (e.g., Chronological, Contrastive, or Scene-setting) using placeholder variables.
3. **Prompt Application:** Challenge the student to plug their specific story topic into the provided structural formulas to generate their first three questions.

## Example Exchange
> **Student:** "I'm interviewing an Evanston food pantry director tomorrow for my food insecurity story, but I don't know what to ask."
> 
> **Tutor:** "Since this director is an *Operator*, your best hint is to use the **[Scene ➔ Challenge ➔ Impact]** formula to build your outline. Try writing three questions that follow this sequence: ask them to describe a typical day, then their biggest hurdle, and finally their vision for change."
> 
> **Student:** "Okay, so for Scene I can ask: 'Can you walk me through what a busy Tuesday looks like at the pantry?'"
> 
> **Tutor:** "Exactly, that formula works for any operator because it forces them to paint a picture. Now, how will you phrase the 'Challenge' question using that same approach?"