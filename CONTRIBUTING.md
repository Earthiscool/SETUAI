# Contributing

## Claim work

Read the kickoff guide and open issues. Comment on the issue you want to help with. Agastya confirms the accountable owner and reviewer before overlapping implementation begins. All starting issues are intentionally unassigned.

Each task needs a goal, owner, reviewer, dependencies, acceptance criteria, and an agreed target. Keep tasks small enough for roughly one to three working sessions.

## Propose a change

1. Update your local copy from the default branch.
2. Create a short-lived branch such as `task/12-lesson-reader`.
3. Make the focused change and check its behavior.
4. Open a pull request referencing the issue.
5. Explain what changed and how it was checked. Include screenshots for visual changes.
6. Ask a peer who understands the changed area to review.
7. Resolve feedback, then merge after approval and applicable checks pass.

Do not self-approve. A team lead title is not required to review. Record a suitable reviewer in the issue. Agastya coordinates if no reviewer is available. Use draft pull requests for incomplete work.

For code changes, use pull requests instead of direct pushes to the default branch. This is a team agreement until repository protection is configured; this guide does not enforce settings.

## Shared decisions

Agree on the stack and data format before implementation. Changes to shared interfaces, dependencies, or data models must be discussed on the issue and reflected in documentation. Tell other owners when your change affects their work.

## Done means

- Acceptance criteria met and evidence recorded.
- Peer review completed and feedback resolved.
- Relevant build/checks pass once they exist.
- Documentation updated if setup or behavior changed.
- Change merged and, for user-facing features, demonstrated in the test environment.
- Follow-up defects recorded as issues.

## Public repository hygiene

Do not commit credentials, private textbook material, personal learner data, or private team contact details. Example configuration must use placeholders. Agastya approves textbook excerpts for publication before they are added.

There is no runnable application yet. Follow the scaffold issue for setup; do not invent installation commands.
