# Changelog

## [Unreleased]

### Added
- Created `.github/workflows/hello-world.yml` to run a Python script that prints "Hello World" using GitHub Actions. (initial commit)
- Updated `README.md` to include a status badge for the workflow. (initial commit)
- Updated the badge URL in `README.md` to explicitly reference the `main` branch for accurate status display. (commit: updated-badge-url)
- Fixed badge URL in `README.md` to use the correct repository owner (`hawaii-in-paradise`) so the badge displays properly. (commit: fix-badge-owner)
- Updated badge in `README.md` to reference the `dev` branch for development tracking. (commit: dev-branch-badge)
- Added `USAGE.md` with instructions for using this workflow as a reusable GitHub Action and tagging as `gha-v.0.0.1`. (commit: add-usage-doc)
- Added both main and dev branch badges to `README.md` to track both workflow statuses. (commit: dual-branch-badges)
- Replaced badges in `README.md` with a labeled table for clear distinction between main and dev branch statuses. (commit: badge-table-labels)
- Updated workflow trigger in `.github/workflows/hello-world.yml` to run on both main and dev branches. (commit: workflow-multi-branch)
- Confirmed both main and dev branch badges now show passing status in `README.md`. (commit: both-badges-passing)
- Created `stage` and `load` branches, added badges for both to the README, and updated all relevant branches. (commit: add-stage-load-branches-badges)

### Instructions to get a working badge
- Push all files, including `.github/workflows/hello-world.yml`, to your GitHub repository (preferably to the `main`, `dev`, `stage`, or `load` branch).
- The badge in `README.md` uses a URL that points to the workflow status on GitHub. It will only display correctly after the workflow has run at least once.
- To trigger the workflow, make any commit (such as this changelog) and push it to GitHub. This will start the workflow and update the badge.
- If your repository is private, ensure you are logged in to GitHub to view the badge.

Once the workflow completes successfully, the badge will show as passing.
