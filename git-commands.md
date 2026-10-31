# Git Commands and Their Purpose

| Command | Purpose |
|---|---|
| git init | Initializes a Git repository |
| git status | Shows the current repository status |
| git add filename | Stages a file |
| git add . | Stages all changes |
| git commit -m "message" | Saves staged changes |
| git log --oneline | Displays compact commit history |
| git diff | Shows unstaged changes |
| git diff --staged | Shows staged changes |
| git branch | Lists branches |
| git switch -c branch-name | Creates and switches to a branch |
| git switch main | Switches to main |
| git merge branch-name | Merges a branch |
| git remote -v | Displays remote repositories |
| git push | Uploads commits |
| git pull | Downloads and integrates remote changes |
| git clone URL | Copies a remote repository locally |

## Merge Conflict

A merge conflict occurs when Git cannot automatically combine changes made to the same part of a file in different branches.

### Resolution
1. Run git status to identify conflicted files.
2. Open the conflicted file.
3. Compare both versions and manually choose the correct content.
4. Remove Git conflict markers.
5. Stage the resolved file using git add.
6. Complete the merge using git commit.

## Conclusion
Git helps track project changes, maintain versions, collaborate through branches and share code using GitHub.
