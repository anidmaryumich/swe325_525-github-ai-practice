# AI Use Record

## AI interaction 1
Date: 2026-10-01
Assistant: Claude
Purpose: Explanation of GitHub objects
Prompt or summary: Explain the difference between a repository, branch, commit, pull request, and issue.
Useful suggestion: A branch is a movable pointer to a line of commits; a commit is a snapshot with a unique SHA that points to its parent; an issue describes work but contains no code; a pull request proposes merging one branch into another and is where review happens. 
Decision: accepted
Reason: The explanation was accurate.
Related GitHub URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice

## AI interaction 2
Date: 2026-10-01
Assistant: Claude
Purpose: Explanation of GitHub history view
Prompt or summary: Explain what a GitHub history view shows.
Useful suggestion: The history view lists a branch's commits newest-first with message, author, date, and SHA; clicking a commit shows its exact line changes; after a merge commit, main's history includes the feature branch's commits plus the merge commit.
Decision: accepted
Reason: It matched what I see in GitHub Desktop's History tab.
Related GitHub URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice

## AI interaction 3
Date: 2026-10-01
Assistant: Claude
Purpose: Proposed improvement and checklist of pull-request description
Prompt or summary: Suggest a checklist for a complete pull-request description, and review my draft pull-request description against it, proposing improvements.
Useful suggestion: A nine-item checklist (title, summary, linked issue with closing keyword, acceptance checklist, commit list, how to verify, AI disclosure, limitations, testing instructions/screenshots) and a proposed improvement to add a "How to verify" section to my draft.
Decision: accepted
Reason: accepted, it is accurate with a good proposed improvement based off the draft I sent.
Related GitHub URL: https://github.com/anidmaryumich/swe325_525-github-ai-practice


## Reflection
1. Which GitHub action or object was most useful to you, and why? The pull request was most useful because it brought everything together in one place.

2. Which AI suggestion did you accept, and what made it useful? I accepted the explanation of the history view. It was useful because I could immediately check it against GitHub Desktop's History tab and use it to confirm that my commits were on the feature branch rather than main.

3. Which AI suggestion did you revise or reject, and why? I didn’t rejected the suggestion to add testing instructions and screenshots to my pull request description but I could because for our case this repository contains only documentation with no code or user interface to test.

4. What did you verify yourself instead of trusting the AI? I confirmed when using it, no leaked private data was put in there.

5. What would you change in your GitHub workflow next time? I would open the pull request earlier, maybe as a draft, so the pull request and commit links are available sooner.
