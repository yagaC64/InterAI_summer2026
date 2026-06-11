# Repository Access Model

This repository uses a minimal-rights collaboration model for class work.

## Roles

| Role | Access | Purpose |
| --- | --- | --- |
| Instructor / repo owner | Admin | Manage settings, review work, merge accepted pull requests, and handle batch imports when needed |
| Students | Public contributor | Fork the repo, open issues, submit pull requests, comment, and review class work |
| Trusted class helper / TA | Collaborator only if approved by the instructor | Help maintain the repo when direct write access is necessary |

## Student Workflow

Students should:

1. Open the public repo.
2. Fork it to their own GitHub account.
3. Create a branch in their fork.
4. Edit the class catalog, scoreboard, docs, or class resource files.
5. Open a pull request back to `yagaC64/InterAI_summer2026:main`.
6. Participate in issue and pull request discussions.

## Why Students Are Not Collaborators

This repo is owned by a personal GitHub account. On personal-account repositories, collaborator access includes write permission.

For this class, students do not need write access to the upstream repository. Forks and pull requests give students the right collaboration practice while keeping the main repo protected.

## Current Guardrails

- The repo is public.
- Issues are enabled.
- Pull requests are the normal path for student changes.
- The `main` branch requires one approving review.
- Conversation resolution is required before merge.
- Force pushes are blocked.
- Branch deletion is blocked.
- Required status checks are not enabled yet because the repo does not have meaningful CI checks.
- The wiki is disabled so class edits stay in the issue and pull request workflow.

## When To Grant More Access

Only invite someone as a collaborator when they are acting as a trusted maintainer or class helper and direct upstream write access is necessary.

If the class needs more granular roles later, move the repo into a GitHub organization and use organization repository roles such as Triage or Write.
