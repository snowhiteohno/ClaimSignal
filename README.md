
# ClaimSignal

Issue-to-PR intelligence for open source repos.

Paste a GitHub issue URL and ClaimSignal tells you:
- whether it is assigned
- linked PRs
- competing drafts
- recent "I'm working on this" comments
- maintainer response latency
- median time-to-merge for first-time contributors in that repo

## Why this exists

Open source contribution is often blocked by uncertainty, not code.

ClaimSignal reduces duplicate effort by revealing whether an issue is truly open, already in motion, or structurally slow to merge.

## Features

- GitHub issue analysis from a single URL
- Assignee and label detection
- PR linkage discovery
- Comment history scan for claim statements
- Maintainer responsiveness metrics
- First-time contributor merge timing stats
- Repo-level contribution friction signal

## Example

```bash
claimsignal analyze https://github.com/org/repo/issues/123
