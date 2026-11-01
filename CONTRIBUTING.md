# Contributing to UniZ

UniZ is built and maintained by students at RGUKT. Anyone can contribute, and most of the work happens in [uniz-master](https://github.com/uniz-rguktong/uniz-master).

## First PR in 5 steps

1. Pick an issue labeled [`good first issue`](https://github.com/uniz-rguktong/uniz-master/issues?q=is%3Aopen+label%3A%22good+first+issue%22) and comment that you're taking it.
2. Fork the repo and branch off `main` (`fix/short-name` or `feat/short-name`).
3. Set up locally with the [setup guide](https://github.com/uniz-rguktong/uniz-master/blob/main/CONTRIBUTING.md). You don't need any production secrets, `secrets.env.example` is enough.
4. Run the same checks CI runs before you push (lint, typecheck, tests, build).
5. Open a PR using the template and link the issue (`Closes #123`).

## PR rules

- One change per PR. Small PRs get reviewed the same day, big ones wait.
- PR titles follow [Conventional Commits](https://www.conventionalcommits.org/): `fix(portal): ...`, `feat(api): ...`, `docs: ...`.
- CI has to be green and a code owner has to approve. PRs are squash merged.
- Never commit `.env`, `secrets.env` or any key. Push protection will block it anyway.
- Don't merge your own PR, even if you have the rights.

## Issues

- Bugs: use the bug form and include steps to reproduce, what you expected and what happened.
- Features: open a feature request or start a thread in Discussions first if it's big.
- Security problems: don't open an issue, see [SECURITY.md](SECURITY.md).

## Getting help

See [SUPPORT.md](SUPPORT.md). How decisions get made and how you become a reviewer is in [GOVERNANCE.md](GOVERNANCE.md).

Everyone here follows the [Code of Conduct](CODE_OF_CONDUCT.md).
