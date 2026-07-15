# OmniVault Emoji Conventions

This file defines the standard emoji vocabulary for OmniVault GitHub work.

The purpose of the system is to make commits, issues, labels, pull requests, workflow records, and future contributor activity easier to scan and understand.

## Core Rule

Every commit message must include at least one relevant emoji.

The emoji should communicate the primary purpose of the change before the rest of the message is read.

## Standard Emoji Vocabulary

| Emoji | Meaning | Use for |
|---|---|---|
| ✨ | New feature | Adding new functionality, capabilities, or major additions |
| 🐛 | Bug fix | Correcting broken or incorrect behavior |
| 📝 | Documentation | README files, guides, notes, rules, comments, or documentation-only changes |
| ♻️ | Refactor | Restructuring code without changing intended behavior |
| 🔧 | Configuration | Configuration files, repository settings, app settings, or environment configuration |
| ✅ | Test / verification | Tests, validation, confirmed checks, or completed verification work |
| 🚀 | Release / deployment | Publishing, deploying, shipping, or release operations |
| 🔒 | Security | Security fixes, access controls, credential handling, or hardening |
| ⬆️ | Dependency upgrade | Updating an existing dependency to a newer version |
| ➕ | Add dependency or component | Adding a new dependency, module, package, or component |
| ➖ | Remove dependency or component | Removing a dependency, module, package, or component |
| 🗑️ | Removal | Deleting obsolete files, code, features, or resources |
| 📦 | Package / files / assets | Packaging, bundles, stored assets, file sets, or distribution content |
| 🎨 | UI / formatting / style | Visual styling, formatting, layout, or non-functional presentation changes |
| ⚡ | Performance | Speed, efficiency, memory, startup time, or optimization improvements |
| 🧪 | Experimental | Prototypes, experiments, temporary trials, or unproven approaches |
| 🚧 | Work in progress | Incomplete work that is intentionally not finished yet |
| 🔀 | Merge / integration | Integrating branches, systems, or major workstreams |
| 🌱 | Initial setup | New repository setup, scaffolding, seed content, or first-time initialization |
| 🏷️ | Tags / labels / metadata | Git tags, issue labels, metadata, naming, or classification work |
| 👷 | CI / workflow / automation | GitHub Actions, CI pipelines, automation, or workflow changes |
| 💚 | Fix CI / workflow failure | Repairing a broken build, failed workflow, or failing automation |
| 🔖 | Version / release tag | Version bumps, release tags, or release identifiers |
| 🔨 | Build system | Build scripts, build tools, compilation, or packaging configuration |
| 🧹 | Cleanup / housekeeping | General cleanup, organization, minor maintenance, or repository housekeeping |
| 💥 | Breaking change | Changes that intentionally break compatibility or require migration |
| 🔊 | Add or improve logging | Adding logs, diagnostics, tracing, or observability output |
| 🔇 | Reduce or remove logging | Removing noisy logs or reducing diagnostic output |
| ♿ | Accessibility | Accessibility improvements or accessibility-specific fixes |
| 🌐 | Localization / language | Translation, localization, locale, or language-related work |
| 💡 | Idea / proposal | Ideas, design proposals, planned concepts, or exploratory discussion |

## Commit Message Rules

1. Every commit message must contain at least one relevant emoji.
2. The emoji must match the primary purpose of the commit.
3. Use one primary emoji by default.
4. Use more than one emoji only when the commit genuinely has multiple equally important purposes.
5. Do not use random or decorative emojis that do not describe the change.
6. The text after the emoji must remain clear and readable on its own.
7. Prefer concise, action-oriented commit messages.
8. Breaking changes must use `💥` when applicable.
9. Security changes must use `🔒` when applicable.
10. Release and deployment changes must use `🚀` or `🔖` when applicable.
11. Workflow and CI changes must use `👷` or `💚` when applicable.
12. New standard meanings must be added to this file before they become part of the official OmniVault vocabulary.

## Commit Message Format

Use this general format:

```text
<emoji> <clear action-oriented summary>
```

Examples:

```text
✨ Add OmniVault issue workflow
🐛 Fix GitHub label handling
📝 Update repository documentation
🔧 Configure Dev branch settings
✅ Verify GitHub connector access
🔒 Harden secret handling rules
👷 Add repository validation workflow
💥 Replace incompatible configuration format
```

## Issue Title Rules

Issue titles may use the same emoji vocabulary so the purpose of an issue is easy to scan.

Examples:

```text
📝 Add emoji conventions
🐛 Fix branch detection
💡 Propose new approval workflow
🔒 Review repository access controls
```

The emoji in an issue title should describe the main purpose of the proposed work.

## Label Rules

Labels may use the same emoji vocabulary where useful.

Examples:

```text
🤖 ChatGPT
💻 Codex
👤 Jacob
✅ Approved
🚧 In Progress
🧪 Experimental
🔒 Security
🐛 Bug
✨ Feature
```

Labels are not required to match commit emojis one-to-one, but shared meanings should stay consistent.

## Approval Workflow Rules

For repository-changing work governed by the OmniVault issue-first workflow:

1. Create an issue before making the change.
2. Describe the exact planned scope in the issue.
3. Assign the issue to the appropriate reviewer or responsible person.
4. Apply the appropriate labels when available.
5. Wait for explicit approval.
6. Verify the approval in the issue before making repository changes.
7. Perform only the approved work.
8. Use the appropriate emoji in every resulting commit message.
9. Report the result back in the issue.
10. Significant scope changes require renewed approval.

## Shared Use

This file is the shared emoji cheat sheet for:

- JacobS
- ChatGPT
- Codex
- Future approved contributors or automation

All participants should use the same meanings so repository history remains consistent and easy to understand.

## Source of Truth

`emojis.MD` is the source of truth for OmniVault emoji meanings.

Repository rules, issue templates, automation, contributor guidance, and future workflow documentation may reference this file instead of redefining the emoji system in multiple places.
