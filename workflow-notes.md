# GitHub Workflow Notes

## Repository
- Repository URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice
- Default branch: main

## Issue
- Issue URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice/issues/1
- Purpose: Defines the goal, acceptance criteria, and task checklist for documenting my GitHub workflow with AI assistance.

## Feature branch
- Branch name: feature/github-ai-workflow
- Branch URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice/tree/feature/github-ai-workflow

## Key GitHub concepts
- Issue: A tracked unit of work that describes a goal, acceptance criteria, and tasks. It explains why the change is needed.
- Branch: An independent line of development. A feature branch lets me make changes without affecting the stable default branch.
- Commit: A saved snapshot of specific changes with a message explaining what changed. Small, focused commits make history easy to read and review.
- Pull request: A proposal to merge one branch into another. It shows the commits and file changes, links the issue, and is where review happens.
- Default branch (main): The stable branch that represents the accepted state of the project. Work reaches it only through a reviewed pull request.

## Links
- Commit 1: Document repository purpose
- Commit 2: Record GitHub workflow
- Commit 3: Add AI-use record
- Pull request
- Merge / repository history: https://github.com/anidmaryumich/swe325_525-github-ai-practice/commits/main

## How the pieces fit together
Issue #1 defined what "done" means through acceptance criteria and a task checklist. I created `feature/github-ai-workflow` from `main` so the default branch stayed stable, and made focused commits on that branch, each referencing the issue. I then opened a pull request from the feature branch into `main`; its description links the issue, lists the commits, and maps the work to the acceptance criteria. A review comment identified a strength and a needed improvement, which I fixed with a new commit on the same branch. Merging the pull request added the work to `main` and closed the issue.
