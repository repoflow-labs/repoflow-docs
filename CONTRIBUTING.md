## Fork-and-Pull Git Workflow

- Fork → clone → upstream: `git remote add upstream https://github.com/repoflow-labs/repoflow-docs.git`
- Branch naming: `feature/<scope>` | `fix/<scope>` | `docs/<scope>` | `chore/<scope>`
- Never commit directly to main
- Rebase on upstream/main before PR; merge commits prohibited

## Commit Message Convention (Angular, enforced)

Format: `<type>(<scope>): <imperative subject ≤72 chars>`

Types: `feat` | `fix` | `docs` | `chore` | `test` | `refactor` | `perf`

Scopes: `guide`, `api`, `ci`

Examples:
- `docs(guide): add Wave maintainer integration walkthrough`
- `docs(api): document new claimRepo XDR format`
- `fix(docs): correct broken links in integration section`
- `chore(ci): add link checker to validation pipeline`

Breaking changes: `BREAKING CHANGE: <description>` in commit footer

## PR Submission Requirements

- All CI checks must pass before requesting review
- Documentation accuracy: all code examples must be tested against contract ABI
- Closes # in PR description
- PR title follows same Angular convention
- Minimum one maintainer approval before merge