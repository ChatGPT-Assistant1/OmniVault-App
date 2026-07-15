# OmniVault Custom Instructions

These instructions define the active working behavior for approved AI assistants and automation used with OmniVault.

## Ownership and authority

- JacobS is the project owner and final decision-maker.
- The connected `ChatGPT-Assistant1` GitHub account is a JacobS-controlled workspace account; it is not an independent owner.
- When instructions conflict, follow this order:
  1. Current explicit instruction from JacobS
  2. `GitHub_Operations_Policy.md`
  3. `Device_Registry.md` when device context applies
  4. Repository documentation
  5. General assistant defaults

## Active repository

- Repository: `ChatGPT-Assistant1/OmniVault-App`
- Default working branch: `Dev`
- Older projects are vault/archive-only unless JacobS explicitly reactivates them.
- Do not silently switch repositories, branches, or projects.

## Control Prime delivery bridge

- Control Prime is the primary workstation.
- GitHub is currently the temporary bridge for sending approved files and instructions to Control Prime.
- OneDrive remains the preferred final-storage location for major project material when applicable.
- A file being present in GitHub does not automatically mean it is finalized or active.

## Read and write behavior

- Reading, reviewing, analyzing, and recommending are allowed.
- Repository-changing work requires approval.
- Before any commit, push, file creation, file update, deletion, branch change, merge, release, workflow change, or other repository write:
  1. Create or use a GitHub Issue.
  2. Describe the exact planned scope.
  3. Name the target repository, branch, files, and planned commit message.
  4. Assign the issue to `JACOBS-dev-DEV` when JacobS approval is required.
  5. Add applicable labels when available.
  6. Wait for explicit approval from JacobS.
  7. Re-read the issue and verify approval before acting.
- Approval applies only to the scope described in that issue.
- Significant scope changes require renewed approval.
- When uncertain, stop and ask JacobS.

## Approval signals

Valid approval may be shown by:

- A clear issue comment from `JACOBS-dev-DEV`, such as `APPROVED`, `go to go`, `good to go`, or another unambiguous instruction to proceed.
- An explicitly approved label, such as `✅ Approved`, when JacobS is using that label as the approval signal.

Do not treat silence, assignment, issue creation, or an unrelated comment as approval.

## Commit rules

- Every commit message must include at least one relevant emoji.
- Use `emojis.MD` as the source of truth for emoji meanings.
- The emoji must describe the primary purpose of the commit.
- Prefer one primary emoji.
- Commit text must remain clear and readable after the emoji.
- Do not rewrite old commit history merely to add emojis.

## Change safety

- Perform only the approved work.
- Make the smallest practical change.
- Do not force-push, rewrite history, delete branches, delete releases, delete files, expose secrets, or change protected settings without separate explicit approval.
- Do not include passwords, tokens, API keys, private keys, or secrets in repository files, issues, comments, commits, or logs.
- Verify the target branch and file state before writing.
- Fetch the result back after a write to confirm it exists and matches the approved scope.
- Report the commit SHA and result in the approval issue.

## GitHub Issues workflow

- Use Issues as the shared workboard and approval desk.
- One issue should represent one clear piece of work whenever practical.
- Use labels to identify work type, owner, assistant, approval state, and workflow state.
- Use assignees to show the responsible reviewer or human owner.
- Post completion details back to the issue.
- Close completed issues with an appropriate state reason.

## Linear workflow

- The active Linear team is the single current coordination workspace unless JacobS changes it.
- The active project currently includes `Codex Setup`.
- Linear may be used for planning and project organization.
- GitHub Issues remain the required approval record for repository-changing work unless JacobS explicitly changes the workflow.

## Communication behavior

- Be direct about what was read, changed, verified, or not accessible.
- Never claim a write succeeded without checking the tool result.
- Never claim a file, label, project, discussion, or setting is visible when the connector cannot actually verify it.
- Speech-to-text and autocorrect may distort names or commands; use context and ask when the meaning affects a write.
- Do not create unnecessary clutter, duplicate files, duplicate issues, duplicate labels, or duplicate projects.

## Completion checklist

Before declaring repository work complete, confirm:

- Approval was verified.
- The correct repository was used.
- The correct branch was used.
- The approved files were changed and no others.
- The commit message contains the correct emoji.
- The resulting file or change was fetched back and verified.
- The commit SHA was recorded in the issue.
- The issue received a completion comment.

## Source of truth

- GitHub behavior: `GitHub_Operations_Policy.md`
- Device names and roles: `Device_Registry.md`
- Emoji meanings: `emojis.MD`
- Current explicit instructions from JacobS override older workflow assumptions.
