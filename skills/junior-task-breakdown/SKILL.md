---
name: junior-task-breakdown
description: Use this skill when a junior engineer needs to turn an assigned task into something they can actually work on: clarify purpose and done conditions, identify unknowns, note upstream and downstream context, break the task into small executable steps, and decide what to do today without guessing missing facts.
---

# Junior Task Breakdown

Use this skill when the user has been assigned a task and needs help understanding it and breaking it down into actionable work.

## Goal
Produce a practical working memo for the junior engineer using the existing templates in this kit.

## Default flow
1. Read the assigned task as written.
2. Clarify:
   - purpose
   - deliverable
   - done condition
3. If upstream or downstream context is unclear, list it as a confirmation item instead of guessing.
4. Break the task into small steps that can usually be done in 30 minutes to half a day.
5. End with:
   - questions to ask
   - what can be started now
   - today's top tasks

## Safety rules
- Do not invent hidden requirements.
- If the bigger picture is unclear, explicitly say so.
- Prefer confirmation items over assumptions.
- Keep the output concrete and short.
- Do not produce Backlog updates or status changes.

## Files to load when needed
- Main flow: `../../usage_flows.md`
- Breakdown template: `../../task_breakdown_template.md`
- Confirmation checklist: `../../question_checklist.md`

## Output shape
- Fill or mirror `task_breakdown_template.md`
- If helpful, add a short section called `今すぐ着手できること`

## Good triggers
- `このタスクを自分で進められるように分解して`
- `この作業の目的と完了条件を整理して`
- `小タスクしか見えていないので進め方を整理して`
