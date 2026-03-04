# Automated GitHub Activity

> **Transparency notice:** This repository exists to automate routine, scheduled commits. It does **not** represent original development work — it is an experiment in GitHub automation and scripting.

---

## What This Is

This repo runs a scheduled script that makes automated commits on a regular basis. The primary purpose is to **explore GitHub Actions workflows, cron scheduling, and scripting automation**, not to artificially inflate a contribution graph.

## Why It Exists

- Learning how GitHub Actions and scheduled workflows (`schedule` trigger) work
- Experimenting with automated git operations in CI/CD environments
- Practicing shell/Python scripting for task automation

## What It Is NOT

- Real feature development or meaningful code changes
- An attempt to fake productivity or deceive employers/collaborators
- A representation of my technical output

## How It Works

A GitHub Actions workflow runs on a cron schedule and makes a small, timestamped commit to this repository. The commit content is trivial (e.g., a log entry or timestamp file update).

```yaml
on:
  schedule:
    - cron: '0 12 * * *'  # Runs daily at noon UTC
```

## Honest Take

GitHub's contribution graph was never meant to be used as a performance metric but it often is. This project was built partly to understand that dynamic, and partly because automated workflows are genuinely useful to learn.

If you're a recruiter or collaborator looking at my profile: please look at my **pinned repositories** for actual work. This repo is infrastructure practice, nothing more.

---

*Feel free to fork this if you want to learn GitHub Actions scheduling yourself.*