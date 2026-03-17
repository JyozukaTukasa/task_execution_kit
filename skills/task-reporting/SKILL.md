---
name: task-reporting
description: Use this skill when someone needs to prepare a work report from facts only: organize completed work, unfinished work, blockers, and next steps into a fixed reporting format without generating free-form status prose or guessing progress.
---

# Task Reporting

Use this skill when the user wants to turn today's actual work into a clean report.

## Goal
Produce a report draft that matches the fixed report format in this kit.

## Default flow
1. Read only the facts the user provides.
2. Separate them into:
   - what was done today
   - what is completed
   - what is not completed
   - blockers or questions
   - next actions
3. Put them into the fixed report structure.

## Safety rules
- Do not write a polished free-form report.
- Do not add work that was not explicitly stated.
- Do not rewrite uncertainty as completion.
- If facts are missing, leave the item blank or note that confirmation is needed.

## Files to load when needed
- Reporting template: `../../work_report_template.md`

## Output shape
- Follow `work_report_template.md`
- Keep each bullet factual and short

## Good triggers
- `今日の作業を報告テンプレートに整理して`
- `この作業内容を固定フォーマットでまとめて`
- `自由文ではなく事実だけで報告を作って`
