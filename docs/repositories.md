# Repository registry

This is the human-facing workspace registry. The canonical machine registry and
AI routing state live in
[`syllik/ai-workflow/workspace.yaml`](https://github.com/syllik/ai-workflow/blob/master/workspace.yaml).
`GitHub state` records only whether a repository is archived.

| Purpose | GitHub repository | Local path | Visibility | Default branch | Integration branch | AI access | AI status | GitHub state |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Profile and workspace navigation | [syllik/syllik](https://github.com/syllik/syllik) | `profile/syllik` | Public | `master` | `master` | Managed | Active | Not archived |
| ChipIn web frontend | [ChipIn-one/chipin-frontend](https://github.com/ChipIn-one/chipin-frontend) | `products/chipin/chipin-frontend` | Public | `main` | `dev` | Managed | Active | Not archived |
| ChipIn backend and API | [ChipIn-one/chipin-backend](https://github.com/ChipIn-one/chipin-backend) | `products/chipin/chipin-backend` | 🔒 Private | `develop` | `develop` | Read-only | Active | Not archived |
| ChatGPT archive cleanup tooling | [syllik/chatgpt-archive-cleanup](https://github.com/syllik/chatgpt-archive-cleanup) | `tools/ai/chatgpt-archive-cleanup` | Public | `main` | `main` | Managed | Active | Not archived |
| Local Codex runner tooling | [syllik/codex-local-runner](https://github.com/syllik/codex-local-runner) | `tools/ai/codex-local-runner` | 🔒 Private | `master` | `master` | Managed | Onboarding | Not archived |
| YouTube metadata localization tooling | [syllik/youtube-metadata-translator](https://github.com/syllik/youtube-metadata-translator) | `tools/content/youtube-metadata-translator` | Public | `main` | `main` | Managed | Active | Not archived |
| Canonical AI workflow and context | [syllik/ai-workflow](https://github.com/syllik/ai-workflow) | `workflows/ai/ai-workflow` | Public | `master` | `master` | Managed | Active | Not archived |
| GPG-signed Git commit guide | [syllik/gpg-signed-commits](https://github.com/syllik/gpg-signed-commits) | `guides/git/gpg-signed-commits` | Public | `main` | `main` | Managed | Active | Not archived |
