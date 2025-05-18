# Instructions for Writing a Commit Message (Semantic Style)

Follow these steps to generate a clear, useful, and conventional commit message. Use the semantic commit format to improve collaboration, changelog generation, and codebase clarity.

## Format

<type>(<scope>): <subject>

- `<type>`: the category of the change.
- `<scope>`: the part of the codebase affected (optional).
- `<subject>`: a short summary of the change in present tense (no punctuation at the end).

## Valid Types

Use one of the following types:

- `feat`: a new feature for the user.
- `fix`: a bug fix that impacts users.
- `docs`: documentation-only changes.
- `style`: changes that do not affect meaning (e.g. formatting, white-space).
- `refactor`: a code change that neither fixes a bug nor adds a feature.
- `test`: adding or refactoring tests without changing production code.
- `chore`: changes to the build process or auxiliary tools (e.g., CI configs, package updates).

## Examples

- feat: add hat wobble animation
- fix(login): prevent crash on empty username
- docs(readme): update installation instructions
- style: format with prettier
- refactor(auth): simplify token validation logic
- test(utils): add tests for date parser
- chore(deps): update lodash to v4.17.21

## Tips

- Write the subject line in the present tense: "add" not "added" or "adds".
- Keep the subject line short (under 72 characters if possible).
- Don’t end the subject line with a period.
