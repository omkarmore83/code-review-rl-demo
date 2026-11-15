# Code review RL demo

Demo mirrors of real pull requests, used to show how different AI code reviewers handled the same change in a Microsoft Foundry reinforcement-learning (RL) demo.

Each mirrored case is one pull request in this repository:

- `demo/<case>-base` holds only the files the original pull request touched, at its base commit.
- `demo/<case>-head` holds the same files at its head commit, so the diff equals the original diff for those files.
- Each AI reviewer's output is posted as one clearly labelled 🤖 review, plus a comment on what the original author fixed later.

These are not real contributions, and nothing is merged. The bot reviews come from a held-out evaluation; they were never posted on the original pull requests, and the original authors never saw them.

## Mirrored cases

| Case | Source (plain text) | Licence | Files copied |
|---|---|---|---|
| `kilocode-13350` | Kilo Code, repository `Kilo-Org/kilocode`, pull request 13350: "fix(vscode): limit Agent Manager document viewer to Markdown plans" | MIT | 4 |

## Attribution and licences

### Kilo Code (`kilocode-13350`)

The files on the `demo/kilocode-13350-base` and `demo/kilocode-13350-head` branches are **files copied for a demo mirror** from Kilo Code (repository `Kilo-Org/kilocode`, pull request 13350; base commit `ed150ae`, head commit `18504df`). They are unmodified copies of the 4 files that pull request touched; nothing else from the project is included. Kilo Code is open source under the MIT License (Copyright (c) 2026 Kilo Code; Copyright (c) 2025 opencode); the full licence text is in [licenses/kilocode-LICENSE](licenses/kilocode-LICENSE).

This repository is not affiliated with or endorsed by the original projects.
