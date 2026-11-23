# Mission 6 — Git and GitHub
## 1. Task / objective
Understand status, staging, commits, history, branches and Pull Requests.
## 2. Work completed
### Task 6.1 — Basic Git workflow
| Git operation | What it does in my words |
|---|---|
| Check repository status | `git status` compares the working files with the tracked repository state. |
| Stage selected changes | `git add <file>` puts chosen changes into the next-commit staging area. |
| Create a commit | `git commit -m "message"` records the staged snapshot with a description. |
| View history | `git log --oneline` lists recent commits and short IDs. |

Staging selects what belongs in the next commit, while a commit permanently records that staged snapshot in local Git history.

### Task 6.2 — Branch
The branch `update-about` was created for a short root-README learning update.

### Task 6.3 — Pull Request
A branch is a separate named line of development; it lets work proceed without immediately changing main. A Pull Request proposes merging one branch into another and gives collaborators a place to review the changes. Pull Request https://github.com/CrackerHacker451/digital-detective-8531/pull/1 was created and merged into main after review.

### Task 6.4 — Git glossary
- Initialize: `git init` creates a local Git repository.
- Check status: `git status` reports staged, unstaged and untracked changes.
- Stage: `git add` selects changes for the next commit.
- Commit: `git commit` records staged changes.
- View history: `git log` displays recorded commits.
- Create/list branches: `git branch <name>` creates one; `git branch` lists them.
- Switch: `git switch <name>` changes the active branch.
- Publish: `git push` sends local commits/branches to a remote.
- Retrieve: `git pull` fetches and integrates remote changes; `git fetch` retrieves remote tracking data without merging.

## 3. Commands / tools used
`git status`, `git add`, `git commit`, `git log --oneline`, `git branch`, `git switch`, `git push`, `git pull`, GitHub branch comparison and Pull Request interface.
## 4. My understanding
Git separates working files, staging and recorded history. GitHub supplies remote hosting and a review workflow. Branches reduce interference, and Pull Requests make proposed changes visible before integration.
## 5. Difficulties faced
No major difficulties; branch and Pull Request steps require careful branch names and remote publishing.
## 6. How I resolved them
Followed Git's output and verified branch/PR activity on GitHub.
## 7. Evidence / files
Git history, `update-about` branch and PR evidence are visible on GitHub; this README describes the workflow.
## 8. Commit details
Commit: `Complete Git and GitHub collaboration mission`; branch activity and pushes were made to GitHub.
