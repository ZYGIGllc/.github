# Contributing (Zygig)

## Branching
- Default branch: `main` (protected)
- Work on short-lived branches: `feat/…`, `fix/…`, `chore/…`
- Ship via pull request; do not push directly to `main`

## One repo per app
Each launchable app gets its own private repository. Shared App Store / Play automation lives in [`ToolsAppDeployment`](https://github.com/ZYGIGllc/ToolsAppDeployment).

## PR checklist
1. Keep PRs focused and reversible
2. CI must pass
3. Prefer conventional commits: `feat:`, `fix:`, `chore:`, `docs:`

## New app repos
Use the **template-app** repository (Template) → “Use this template”. It already includes ToolsAppDeployment callers and `appconnect.yml`.
