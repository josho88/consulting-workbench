# Consulting Workbench

Shared code and working notes for Josh and Matt's consulting projects. Keep the repository small and add infrastructure when a project needs it.

## Layout

- `docs/` — short technical notes and decisions
- `projects/` — one folder per piece of work, with its own README and dependencies
- `shared/python/` and `shared/r/` — code reused across projects
- `notebooks/` — general exploration; project notebooks belong with their project

## Working together

1. Create a short-lived branch for substantial changes and open a pull request for review. Small edits can go straight to `main` if agreed together.
2. Document setup and run commands in each project's README. Keep dependencies alongside the project.
3. Keep commits focused. Never commit credentials, local environment files, raw client data or confidential deliverables. Use synthetic examples where needed.
4. Agree client data storage and access before real data is used.

## Initial stack

VS Code with Python or R as needed; GitHub for code; Notion for plans and documents; Slack for messages; Granola for meeting notes once both accounts work. Choose Josh's Azure or AWS subscription when a real cloud workload arises. No data warehouse or deployment platform is needed yet.
