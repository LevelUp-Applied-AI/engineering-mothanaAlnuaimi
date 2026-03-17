# Summary
This PR improves the repository’s pull request workflow and contributor guidance by adding a reusable PR template, a self-review checklist, and clearer run instructions in the README.

## What changed
- Added `.github/pull_request_template.md` with structured PR sections for summary, changes, testing, notes, and checklist items
- Added `docs/pr-checklist.md` containing a pre-PR self-review checklist
- Updated `README.md` to include a **How to run** section with environment setup, dependency installation, and execution steps

## Why
- This PR improves pull request quality and makes submissions more consistent and review-friendly
- It helps contributors explain their changes clearly and reduce avoidable mistakes before submission
- It also gives reviewers and contributors clear instructions to set up, run, and verify the project locally

## How to test
> From the repo root:
1. Activate the virtual environment
2. Install dependencies: `pip install -r requirements-prework.txt`
3. Run the sanity check: `python scripts/sanity.py`
4. Optional: run tests with `pytest -q`

## Notes / Screenshots (optional)
- This PR only adds documentation and workflow-support files
- No source logic or functional behavior was changed
- The goal is to improve clarity, consistency, and review readiness

## Checklist
- [x] My PR title describes the change clearly
- [x] I ran the app/tests locally and they pass
- [x] I kept the scope focused (one change-set)
- [x] I removed debug prints/breakpoints and temporary files
- [x] I updated docs/README if behavior or usage changed
