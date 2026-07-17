# AGENTS.md

This project file is intentionally lightweight.

Global rules are defined in `/root/.openclaw/workspace/AGENTS.md`.

## Автоматизация задач (Kimi Code CLI)

Задачи для Kimi оформляются в `tasks/` (см. `tasks/WORKFLOW.md`). Активная задача — в `tasks/ACTIVE.md`. Push в `main` с изменением `tasks/ACTIVE.md` или `tasks/TASK-*.md` автоматически запускает Kimi через GitHub Action: создаётся ветка `kimi/<TASK-ID>` и Pull Request. Результат проверяется по PR перед merge.
