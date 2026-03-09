# Pre-PR Self-Review Checklist

- [ ] The change does what the PR title/description claims (manual sanity check).
- [ ] I ran automated checks locally (tests/lint/format if available) and they pass.
- [ ] I added/updated tests for new behavior or bug fixes (or explained why not).
- [ ] README/docs match the current behavior (commands, env vars, expected output).
- [ ] Scope is focused: no unrelated refactors, renames, or “drive-by” changes.
- [ ] No debug artifacts: no `print()`, `breakpoint()`, commented-out code, or temp files.
- [ ] I reviewed the diff myself from GitHub’s “Files changed” view before submitting.