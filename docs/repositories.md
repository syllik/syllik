# Repository registry

This is the human-facing workspace registry. The canonical machine registry and
AI routing state live in
[`syllik/ai-workflow/workspace.yaml`](https://github.com/syllik/ai-workflow/blob/master/workspace.yaml).
`GitHub state` records only whether a repository is archived.

| Purpose | GitHub repository | Local path | Visibility | Default branch | Integration branch | AI access | AI status | GitHub state |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Profile and workspace navigation | [syllik/syllik](https://github.com/syllik/syllik) | `profile/syllik` | Public | `master` | `master` | Managed | Active | Not archived |
| Personal tasks, plans, research and reminders | [syllik/life-ops](https://github.com/syllik/life-ops) | `personal/life-ops` | 🔒 Private | `master` | `master` | Managed | Active | Not archived |
| Telegram interface for Life Ops | [syllik/life-ops-bot](https://github.com/syllik/life-ops-bot) | `personal/life-ops-bot` | Public | `master` | `master` | Managed | Onboarding | Not archived |
| ChipIn web frontend | [ChipIn-one/chipin-frontend](https://github.com/ChipIn-one/chipin-frontend) | `products/chipin/chipin-frontend` | Public | `main` | `dev` | Managed | Active | Not archived |
| ChipIn backend and API | [ChipIn-one/chipin-backend](https://github.com/ChipIn-one/chipin-backend) | `products/chipin/chipin-backend` | 🔒 Private | `develop` | `develop` | Read-only | Active | Not archived |
| ChipIn shared product/domain knowledge | [ChipIn-one/chipin-knowledge-base](https://github.com/ChipIn-one/chipin-knowledge-base) | `products/chipin/chipin-knowledge-base` | 🔒 Private | `main` | `main` | Read-only | Active | Not archived |
| ChipIn organization GitHub coordination | [ChipIn-one/.github](https://github.com/ChipIn-one/.github) | `products/chipin/.github` | Public | `main` | `main` | Managed | Active | Not archived |
| ChatGPT archive cleanup tooling | [syllik/chatgpt-archive-cleanup](https://github.com/syllik/chatgpt-archive-cleanup) | `tools/ai/chatgpt-archive-cleanup` | Public | `main` | `main` | Managed | Active | Not archived |
| Historical MIT runner source for Deep Dark Factory | [syllik/codex-local-runner-archive](https://github.com/syllik/codex-local-runner-archive) | `tools/ai/codex-local-runner-archive` | Public | `master` | — | Not registered | Retired reference | Archived |
| YouTube metadata localization tooling | [syllik/youtube-metadata-translator](https://github.com/syllik/youtube-metadata-translator) | `tools/content/youtube-metadata-translator` | Public | `main` | `main` | Managed | Active | Not archived |
| Provider-neutral software factory execution infrastructure | [syllik/deep-dark-factory](https://github.com/syllik/deep-dark-factory) | `infrastructure/ai/deep-dark-factory` | Public | `master` | `master` | Managed | Active | Not archived |
| Canonical AI workflow and context | [syllik/ai-workflow](https://github.com/syllik/ai-workflow) | `workflows/ai/ai-workflow` | Public | `master` | `master` | Managed | Active | Not archived |
| GPG-signed Git commit guide | [syllik/gpg-signed-commits](https://github.com/syllik/gpg-signed-commits) | `guides/git/gpg-signed-commits` | Public | `main` | `main` | Managed | Active | Not archived |

The runner was retired on 2026-10-10. Its original
[`syllik/codex-local-runner`](https://github.com/syllik/codex-local-runner) remains
private and archived, with no retained local runtime checkout. The public archive
is historical reference outside the canonical machine registry, not an active
runner or a managed AI target. `syllik/codex-local-runner-control` was already
deleted on 2026-09-06, confirmed in the owner's GitHub deleted-repository list.
See the archive's
[DDF lessons](https://github.com/syllik/codex-local-runner-archive/blob/master/docs/DDF-LESSONS.md)
and [dependency audit](https://github.com/syllik/codex-local-runner-archive/blob/master/docs/DEPENDENCY-AUDIT.md)
before reusing its code.
