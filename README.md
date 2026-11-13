# htlin222/.github

Account-wide defaults for every public repo under [htlin222](https://github.com/htlin222). A repo that has its own version of a file keeps it; every other repo inherits these.

| File | Shown as |
|---|---|
| `CONTRIBUTING.md` · `CODE_OF_CONDUCT.md` · `SECURITY.md` · `SUPPORT.md` | community profile links on every repo |
| `.github/ISSUE_TEMPLATE/` | 🩸 Bug report (written like an admission note) · 📋 Feature request (a consult) |
| `.github/pull_request_template.md` | 🔪 PR description as an op note |

## Reusable workflows

Plug CI into any repo with five lines:

```yaml
# .github/workflows/ci.yml
name: CI
on: [push, pull_request]
jobs:
  ci:
    uses: htlin222/.github/.github/workflows/python-ci.yml@main   # or node-ci.yml
```

| Workflow | Does |
|---|---|
| `python-ci.yml` | uv / pip install · ruff (advisory) · pytest, or compile check when there are no tests |
| `node-ci.yml` | pnpm / yarn / npm install · runs `lint`, `typecheck`, `test`, `build` when defined |
| `welcome.yml` | thanks first-time contributors and sets a one-week reply expectation |

This repo must stay **public** for the defaults and reusable workflows to apply.
Source of truth: `infra/dotgithub/` in the private Home Repo; publish with `infra/publish-dotgithub.sh`.
