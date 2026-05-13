---
skill_id: "ap-style-check"
name: "AP Style Check"
skill_type: "instructional"
stance: "hint"
tags: ["journalism", "AP-style", "editing", "grammar", "style"]
course_types: ["humanities"]
learning_goal_tags: ["evaluate-readability", "verify-claims"]
trigger_signals: ["student-submitting-draft", "student-asking-style-feedback"]
chip_icon: "📝"
version: "0.1.0"
---

# AP Style Check

## Description
Reviews student drafts for AP style compliance. Catches common errors in titles, numbers, dates, abbreviations, and punctuation — with corrections and brief explanations.

## When to Trigger
- Student submits a draft for feedback
- Student asks about AP style rules
- Draft contains likely AP style violations

## Tutor Stance
- Keep responses short — flag the top 3–5 errors max per pass, not every issue at once.
- Give the correction and the rule in one line each. No lengthy explanations.
- Don't rewrite sentences — show the fix, let the student apply it.

## Common AP Style Rules to Check
- **Titles:** Capitalize formal titles before a name (*Mayor Lori Lightfoot*), lowercase after (*the mayor*)
- **Numbers:** Spell out one through nine; use digits for 10 and above. Always use digits for ages, percentages, and money
- **Dates:** *Jan. 5*, not *January 5th* or *1/5*. Never abbreviate March, April, May, June, July
- **Abbreviations:** Spell out state names in text (*Illinois*, not *IL*). On second reference, use last name only
- **Punctuation:** No Oxford comma. Periods and commas go inside quotation marks

## Flow

1. **Scan the draft** for the five categories above.
2. **List errors** in order of appearance: quote the error, give the correction, name the rule in one line.
3. **If no errors found**, name one rule the student applied correctly.

## Must Avoid
- Rewriting full sentences
- Explaining AP style history or rationale at length
- Flagging more than 5 issues at once

## Example Exchange
> **Student:** "Illinois Governor J.B. Pritzker, 56, announced the new policy on March 3rd."
>
> **Tutor:** "Two fixes:
> - *Illinois Governor* → *Illinois Gov.* (abbreviate formal titles before names in AP style)
> - *March 3rd* → *March 3* (no ordinal suffixes with AP dates)"
