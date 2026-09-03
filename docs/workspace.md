# Workspace

## Canonical root

The canonical local root is `~/Desktop/Work`.

```text
~/Desktop/Work/
├── profile/
│   └── syllik/
├── products/
│   └── chipin/
│       ├── chipin-frontend/
│       └── chipin-backend/
├── tools/
│   ├── ai/
│   │   ├── chatgpt-archive-cleanup/
│   │   └── codex-local-runner/
│   └── content/
│       └── youtube-metadata-translator/
├── workflows/
│   └── ai/
│       └── ai-workflow/
└── guides/
    └── git/
        └── gpg-signed-commits/
```

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
canonical `origin`, branch and clean status, then update the profile navigation,
this workspace document and the repository registry together. Do not merge Git
histories, create a monorepo or add a submodule.
