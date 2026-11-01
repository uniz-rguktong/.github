# Governance

UniZ is a student run project. This is how it works today. It will change as more people join.

## Roles

- **Contributor**: anyone with a merged PR.
- **Triager**: helps label issues, reproduce bugs and answer Discussions. Gets the Triage role on the org.
- **Reviewer**: owns an area in `CODEOWNERS` and reviews PRs there.
- **Maintainer**: merges PRs, manages releases and production deploys. Right now that's @sreecharan-desu.

How to move up is in the [contributor ladder](https://github.com/uniz-rguktong/uniz-master/blob/main/docs/org/contributor-ladder.md).

## Decisions

- Day to day: the reviewer for that area decides in the PR.
- Bigger changes (new service, schema change, new dependency in the hot path, anything touching auth or student data): open an issue or Discussion first. A maintainer signs off before work starts.
- If people disagree and it doesn't settle in the thread, the maintainer makes the call and writes down why.

## Production

Only maintainers deploy. Merges to `main` deploy automatically, so a merge is a release. Secrets live on the VPS and in Actions secrets and are never shared with contributors.

## Stepping down

If a reviewer or triager is inactive for 6 months, they move to emeritus and can come back any time by asking.
