# ClaimSignal

Contribution intelligence for open source development.

ClaimSignal helps contributors evaluate an issue before investing time into solving it.

Given a GitHub issue URL, ClaimSignal analyzes repository activity and surfaces signals that are usually hidden across comments, pull requests, maintainer discussions, and contributor history.

The result is a practical answer to a simple question:

**Is this issue actually worth working on?**

## Insights Generated

### Ownership Analysis

Identify:

- Current assignees
- Previous assignees
- Active contributors discussing the issue
- Unofficial claims made in comments

### Pull Request Discovery

Locate:

- Linked pull requests
- Open draft pull requests
- Recently closed attempts
- Competing implementations

### Maintainer Behavior

Measure:

- Average response latency
- Review turnaround time
- Merge frequency
- Maintainer participation rate

### Contributor Success Metrics

Calculate:

- Median merge time
- First-time contributor success rate
- Average review cycles
- Repository contribution friction

## Example

```bash
claimsignal analyze https://github.com/org/repo/issues/123
```

## Sample Output

```text
Issue Status:
Active

Assignment:
Unassigned

Competing Work:
2 draft pull requests found

Maintainer Response Time:
14.2 days

First-Time Contributor Median Merge:
31 days

Recommendation:
High risk of duplicate effort.
```

## Use Cases

- Choosing contribution targets
- Avoiding duplicate work
- Evaluating repository health
- Planning open source participation
- Contributor research

## Roadmap

- Browser extension
- GitHub App integration
- Repository opportunity ranking
- Issue recommendation engine
- Contributor matching

## License

MIT
