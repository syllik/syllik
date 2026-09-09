# Workspace

## Canonical root

The canonical local root is `~/Desktop/WORK`.

## Workspace tree

- `profile/`
  - [`syllik/`](https://github.com/syllik/syllik)
- `products/`
  - `chipin/`
    - [`chipin-frontend/`](https://github.com/ChipIn-one/chipin-frontend)
    - [`chipin-backend/`](https://github.com/ChipIn-one/chipin-backend)
- `tools/`
  - `ai/`
    - [`chatgpt-archive-cleanup/`](https://github.com/syllik/chatgpt-archive-cleanup)
    - [`codex-local-runner/`](https://github.com/syllik/codex-local-runner)
  - `content/`
    - [`youtube-metadata-translator/`](https://github.com/syllik/youtube-metadata-translator)
- `workflows/`
  - `ai/`
    - [`ai-workflow/`](https://github.com/syllik/ai-workflow)
- `guides/`
  - `git/`
    - [`gpg-signed-commits/`](https://github.com/syllik/gpg-signed-commits)

## Structure rules

- The workspace uses purpose-first top-level categories: `profile`, `products`,
  `tools`, `workflows` and `guides`.
- Every leaf directory is an independent Git repository with its own `.git`,
  history, branches, remotes, visibility and workflow.
- A leaf directory name matches its GitHub repository name.
- The repositories are not combined into a monorepo and no Git submodules are
  used.
- Repositories outside the approved mapping are excluded from this workspace
  documentation and are not moved or mutated by this structure.

## Adding a project safely

Add a new project only after an explicit user decision. Create or move one
independent repository into a purpose-first leaf directory, verify its
canonical `origin`, branch and clean status, then update this workspace
document and the repository registry together. Do not merge Git histories,
create a monorepo or add a submodule.
