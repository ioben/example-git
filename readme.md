Example Git
===========

- What is Git?
  - DAG of filesystem snapshots
    - What is a DAG?
  - Full files, not diffs
- Untracked vs tracked
- States of tracked files: unmodified, modified, staged
  ![Git commit flow](https://git-scm.com/book/en/v2/images/lifecycle.png)
- `git init`
  - Create a new git repository
  - Alternatively use an existing repository with `git clone`
- `git add`
  - Begin tracking files, stage files
- `git status`
  - View status of files in Git repository
- `git commit`
  - Commit tracked/staged files
- `git log`
  - Show history of git commits
  - Useful flags
    - `-p` Show changes
    - `--oneline` Makes history output more brief
    - `-S` pickaxe, find commits with certain contents
- `git branch`
  - Create/manage branches!
- `git checkout`
  - Change branches/workspace!

Additional Resources
--------------------

- [Git Pro](https://git-scm.com/book/en/v2)
