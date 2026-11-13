# AGENTS.md

## Repository purpose

This repository is the GitHub profile repository for `Laloaobes`.

Its primary artifact is `README.md`, which presents Eduardo Lezama's professional profile, technical skills, selected projects, and contact information.

Treat this repository primarily as a professional portfolio and personal-branding surface rather than as an application codebase.

The profile should balance:

- job opportunities,
- freelance and client opportunities,
- portfolio presentation,
- and professional personal branding.

## Source of truth

Use repository evidence and explicit user-provided information as the source of truth.

Do not invent or imply unsupported:

- professional experience,
- clients,
- employers,
- project ownership,
- responsibilities,
- technologies,
- certifications,
- metrics,
- users,
- revenue,
- performance improvements,
- dates,
- awards,
- testimonials,
- contact details,
- or other factual claims.

Technologies mentioned in the profile describe the user's skills or project experience. They are not automatically dependencies or tooling used by this repository.

If information that would improve the profile is unavailable, omit it rather than guessing.

When a real personal or contact value is needed but only a placeholder is available, ask the user for the correct value before replacing it. Do not search for private contact details on the user's behalf.

## README design freedom

Codex may substantially redesign `README.md` when the requested task is to improve, modernize, optimize, or redesign the profile.

It may freely:

- restructure the page,
- reorder sections,
- rewrite headings,
- rewrite profile copy,
- rewrite project descriptions,
- improve professional positioning,
- improve clarity and persuasiveness,
- change Markdown and embedded HTML,
- replace or reorganize badges,
- add or remove nonessential visual widgets,
- introduce new sections,
- remove weak or redundant README sections,
- change the visual hierarchy,
- change the presentation style,
- and replace the existing design entirely when doing so materially improves the profile.

Do not preserve the current layout merely for historical consistency.

Prefer the strongest overall presentation for the user's professional goals.

## Writing and positioning

Profile copy may be rewritten freely to make it:

- professional,
- concise,
- persuasive,
- technically credible,
- easy to scan,
- and useful to recruiters, potential clients, and collaborators.

Improve wording without changing unsupported facts into claims.

Avoid exaggerated marketing language, vague superlatives, artificial enthusiasm, and claims that cannot be verified from repository evidence or user-provided context.

Do not fabricate metrics merely to make project descriptions sound stronger.

Emphasize demonstrated capabilities, responsibilities, integrations, technical decisions, and delivered functionality when those facts are supported.

## Language

Codex may choose Spanish, English, or a bilingual presentation according to the goal of the requested redesign.

Choose the language strategy that best supports the intended audience.

Keep terminology internally consistent within each section and avoid awkward unnecessary mixing of languages.

If the user explicitly requests a language, follow that request.

## Technologies and skills

Codex may reorganize, regroup, prioritize, or remove technologies from the visible skills presentation when this improves the profile.

Prefer highlighting technologies that are most relevant to the professional positioning and supported by existing repository content or explicit user information.

Do not add a technology merely because it is commonly associated with another listed technology.

Do not infer that a technology shown in `README.md` is installed or used to build this repository.

## Featured projects

Codex may decide which supported projects deserve prominence.

It may:

- change project ordering,
- change presentation format,
- rewrite descriptions,
- consolidate repetitive details,
- highlight relevant technical work,
- and reduce emphasis on projects that contribute less to the overall profile.

Do not invent project facts.

When project information is incomplete, use only what is supported rather than filling gaps with plausible assumptions.

When editing a project entry, keep its title, description, technologies, links, images, and related presentation internally consistent.

## External services and dynamic content

External badges, cards, statistics, widgets, generated graphics, or similar services may be used when they provide meaningful value.

Use them selectively.

Prefer a smaller number of useful, reliable elements over a crowded collection of badges or widgets.

Avoid making the profile unnecessarily dependent on fragile external services.

Do not add an external integration only because it is visually impressive.

When modifying an external URL or generated asset, check that its syntax and intended destination remain valid.

## Repository assets

Codex may create new supporting files when they materially improve the profile, including:

- images,
- SVG assets,
- generated graphics,
- GIFs,
- supporting directories,
- and GitHub Actions workflows.

Keep new assets organized and use clear, stable paths.

Prefer repository-hosted assets when that improves reliability or maintainability.

Do not add files that have no clear purpose.

### Deletion boundary

Do not delete an existing file or repository asset without explicit user confirmation.

This restriction applies even when a redesign would make the file obsolete.

README content and individual README sections may be removed or replaced as part of an approved redesign; deleting a repository file itself requires confirmation.

## GitHub Actions

GitHub Actions workflows may be introduced when they provide a clear improvement to the profile, such as maintaining useful generated content.

Prefer simple workflows with a narrow purpose.

Do not introduce workflow automation when a static solution is sufficient.

Before adding a workflow:

1. confirm that it directly supports the profile,
2. minimize permissions,
3. avoid unnecessary dependencies,
4. avoid secrets when possible,
5. and keep the workflow understandable and maintainable.

Do not assume an existing build, test, package, or deployment workflow unless repository files demonstrate one.

## Secrets and credentials

Prefer solutions that require no secrets, API keys, credentials, or private tokens.

Never invent credentials.

Never place secrets directly in:

- `README.md`,
- workflow files,
- scripts,
- generated assets,
- committed configuration,
- logs,
- or examples that could be mistaken for real credentials.

If a valuable improvement genuinely requires a secret or credential, explain why it is necessary and obtain explicit user approval before introducing that dependency.

If `.env` files, credentials, certificates, private keys, tokens, or other sensitive material appear in the repository:

- do not expose their contents,
- do not copy them into other files,
- do not modify them casually,
- and stop for user guidance if access to them is necessary to complete the task safely.

## Dependencies and tooling

This repository currently functions as a profile repository.

Do not invent a package manager, build system, framework, formatter, linter, test suite, or runtime command merely because technologies are mentioned in the profile.

Only use repository-specific commands when supported by files present in the repository or explicitly supplied by the user.

Prefer static and low-maintenance solutions.

Introduce external dependencies only when they provide a clear advantage over a simpler approach.

Do not add a framework or application toolchain merely to render or maintain the GitHub profile unless the requested feature genuinely requires it.

## Working tree safety

Before making substantial changes, inspect the relevant existing files and the working-tree state.

If unrelated user changes are already present:

- preserve them,
- work around them when possible,
- and do not revert, overwrite, reset, or discard them.

Do not use destructive Git operations to clean the workspace.

The presence of unrelated changes is not by itself a reason to stop unless they make the requested modification unsafe or ambiguous.

## Git boundaries

Codex may modify repository files required by the task.

Codex must not:

- create commits,
- amend commits,
- push to a remote,
- force-push,
- create or delete remote branches,
- publish releases,
- or otherwise change remote Git state.

Leave commits and pushes to the user.

Do not discard existing user changes.

## Validation

Validate proportionally to the files changed.

For README and profile changes, check as applicable:

- Markdown structure,
- embedded HTML structure,
- relative paths,
- local asset references,
- modified external links,
- image references,
- consistency between project descriptions and technology labels,
- obvious duplicated or broken content,
- and the relationship between newly created supporting files and the README.

For workflow changes, also inspect:

- YAML structure,
- action references,
- event triggers,
- required permissions,
- expected generated paths,
- and whether secrets are required.

Do not invent test or lint commands when the repository does not provide them.

Use repository-supported validation tools when they exist.

## Scope and simplicity

Prefer the simplest implementation that produces a strong professional profile.

Do not create architecture, dependencies, automation, configuration, documentation, or support files without a concrete need.

Avoid generic repository boilerplate that does not apply to this profile.

Keep permanent repository instructions focused on durable constraints rather than task-specific preferences.

## Task completion

At the end of a task, report concisely:

- files created or modified,
- the meaningful changes made,
- validation performed,
- anything that could not be verified,
- any external dependency introduced,
- and any action still required from the user.

Do not report a commit or push unless the user performed it separately.

If a requested improvement requires unsupported personal or project facts, identify the missing information instead of inventing it.
