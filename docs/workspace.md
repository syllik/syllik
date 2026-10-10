# Workspace

## Canonical root

The canonical local root is `~/Desktop/WORK`.

## Workspace tree

- `profile/`
  - [`syllik/`](https://github.com/syllik/syllik)
- `personal/`
  - [`life-ops/`](https://github.com/syllik/life-ops)
  - [`life-ops-bot/`](https://github.com/syllik/life-ops-bot)
- `products/`
  - `chipin/`
    - [`chipin-frontend/`](https://github.com/ChipIn-one/chipin-frontend)
    - [`chipin-backend/`](https://github.com/ChipIn-one/chipin-backend)
    - [`chipin-knowledge-base/`](https://github.com/ChipIn-one/chipin-knowledge-base)
    - [`.github/`](https://github.com/ChipIn-one/.github)
- `tools/`
  - `ai/`
    - [`chatgpt-archive-cleanup/`](https://github.com/syllik/chatgpt-archive-cleanup)
    - [`codex-local-runner-archive/`](https://github.com/syllik/codex-local-runner-archive) — archived MIT reference for Deep Dark Factory; excluded from executable AI routing
  - `content/`
    - [`youtube-metadata-translator/`](https://github.com/syllik/youtube-metadata-translator)
- `infrastructure/`
  - `ai/`
    - [`deep-dark-factory/`](https://github.com/syllik/deep-dark-factory)
- `workflows/`
  - `ai/`
    - [`ai-workflow/`](https://github.com/syllik/ai-workflow)
- `guides/`
  - `git/`
    - [`gpg-signed-commits/`](https://github.com/syllik/gpg-signed-commits)

## Structure rules

- The workspace uses purpose-first top-level categories: `profile`, `personal`,
  `products`, `tools`, `infrastructure`, `workflows` and `guides`.
- Every leaf directory is an independent Git repository with its own `.git`,
  history, branches, remotes, visibility and workflow.
- A leaf directory name matches its GitHub repository name.
- The repositories are not combined into a monorepo and no Git submodules are
  used.
- Repositories outside the approved mapping are excluded from this workspace
  documentation and are not moved or mutated by this structure.

## Retired runner

The former `tools/ai/codex-local-runner` checkout and local runtime were removed
on 2026-10-10. Its private original repository is archived. The public source
archive above preserves unfinished work and
[reuse lessons](https://github.com/syllik/codex-local-runner-archive/blob/master/docs/DDF-LESSONS.md)
for Deep Dark Factory; it is not an active workspace execution target.
`codex-local-runner-control` was already deleted on 2026-09-06. Before reusing
archived code, resolve its
[documented dependency vulnerabilities](https://github.com/syllik/codex-local-runner-archive/blob/master/docs/DEPENDENCY-AUDIT.md).

## Adding a project safely

Add a new project only after an explicit user decision. Create or move one
independent repository into a purpose-first leaf directory, verify its
canonical `origin`, branch and clean status, then update this workspace
document and the repository registry together. Do not merge Git histories,
create a monorepo or add a submodule.
