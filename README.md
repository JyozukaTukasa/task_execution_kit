# Task Execution Kit

このキットは、**割り振られたタスクを自分で進められる形にするための Skill セット**です。

## Skill の使い分け

- `task-breakdown`
  - タスクを分解したい時に使う
  - 目的、成果物、完了条件、不明点、今すぐ着手できることを整理する
- `task-reporting`
  - 作業報告をまとめたい時に使う
  - 事実だけを固定フォーマットに整理する

## まずどう使うか

1. 割り振られたタスクを貼る
2. `task-breakdown` で分解する
3. 分からないことは確認事項として残す
4. 作業する
5. `task-reporting` で報告をまとめる

## AI への指示

### 1. タスクを分解したい時

```text
task-breakdown を使ってください。
このタスクを、自分で進められるように分解してください。
目的、成果物、完了条件、不明点、今すぐ着手できることを整理してください。
もし仕様が曖昧なら、実装タスクにせず、先に調査タスクと確認事項に分けてください。
```

### 2. 作業報告をまとめたい時

```text
task-reporting を使ってください。
今日やった作業内容を、固定フォーマットの報告に整理してください。
自由文は作らず、事実だけを分けてください。
```

## 最初に見るファイル

1. [usage_flows.md](./usage_flows.md)
2. [task_breakdown_template.md](./task_breakdown_template.md)
3. [work_report_template.md](./work_report_template.md)

## 補足

- タスク分解の雛形: [task_breakdown_template.md](./task_breakdown_template.md)
- 確認事項の観点: [question_checklist.md](./question_checklist.md)
- 報告の雛形: [work_report_template.md](./work_report_template.md)
