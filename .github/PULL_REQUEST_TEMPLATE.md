## Summary

<!-- Briefly describe what changed and why. -->

## Linked issue(s)

<!-- Replace this comment with actual issue references:
     - Use "Closes #123" ONLY when this PR fully satisfies the issue's acceptance criteria.
     - Use "Refs #123" for partial work or follow-ups that must remain open.
     - Add one line per issue as needed.
     - GitHub closes linked issues only when the PR is merged into the repository's default branch.
     Never imply an issue is complete based solely on passing tests. -->

## Changes and scope

<!-- Describe key changes, approved scope, and anything deliberately excluded. -->

## Requirements provenance

<!-- Identify the approved requirements used for implementation and independent review.
     For repository specs, provide the committed path and exact spec commit SHA;
     include a version only if the spec explicitly defines one.
     For issue-only scope, provide the issue URL/number and approved acceptance-criteria
     snapshot or digest; record reapproval if that scope changed. -->
- **Approved requirements:** <!-- spec path + SHA [+ defined version], or issue + acceptance-criteria snapshot/digest -->
- **Verified requirements baseline:** <!-- exact baseline commit SHA / applicable ref -->
- **Pre-implementation spec reachability:** <!-- evidence each spec commit is reachable from that baseline; or N/A for approved issue-only scope -->
- **Changes after approval:** <!-- none, or linked reapproval evidence -->

## Verification

<!-- List exact commands, outcomes, test counts, skipped tests, and CI results.
     Explicitly note what was not tested or could not be verified. -->

- [ ] Focused tests completed (or reason omitted documented)
- [ ] Dependent/integration tests considered for shared contract changes
- [ ] Full repository-approved verification run (or limitation documented)
- [ ] Independent review findings resolved or documented

## Safety and deferred work

<!-- Note changes to external side effects, database or migration behavior, idempotency,
     authentication, data/privacy handling, or other safety boundaries.
     Record remaining risks and link follow-up issues. Use "Refs #..." for partial work. -->

## Merge checklist

- [ ] All fully resolved issues use `Closes #...`; incomplete work uses `Refs #...`
- [ ] PR scope and verification evidence match the current commit
- [ ] Before implementation, verified each required repository specification commit was reachable from the recorded requirements baseline; stopped and resolved any unverifiable baseline (or documented N/A for issue-only scope)
- [ ] Required repository specifications are committed and included in this PR or already in the default branch
- [ ] Issue-only acceptance criteria match the approved snapshot/digest, or reapproval is documented
- [ ] Every worktree returned by `git worktree list --porcelain` was individually inspected for staged, unstaged, untracked, or unfinished work; all unresolved items are reported below, and human-owned changes preserved (or N/A with reason)
- [ ] CI status checked for the exact PR head commit
- [ ] Human owner has approved merging

**Unresolved worktree items:** <!-- none, or list each path, pending work/status, owner, and disposition/next action; do not silently abandon changes -->

<!-- This template is shared by devbytaylor organization repositories without a
     repository-specific PR template. It documents expectations; it is not a CI gate. -->
