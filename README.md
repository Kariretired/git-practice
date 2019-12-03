# Practice repository to start learning Git

# Commands used

- git init: Create a repository
- git status: compare working directory, staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show history of project commits
- git branch: List branches
- git checkout -b: create branch, then check it checkout

# What's a branches?
A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're "on" that branch. When we make a commit whlie we're on a branch, the branch is updated to ref(er) to the new commit.

# What's HEAD

HEAD is a ref(erence) to the "current" branch (or sometimes a commit ...more that later). Git commands like `status`, `log`, and `branch` use HEAD. `git checkout` updates HEAD to ref(er) to a different branch.

# Commit messages

Default editor is vim (this can be changed)
- `i` to enter *insert* mode
- Type commit message
- `Esc` -> `:wq` -> `Enter` to write message and quit
Or use `git commit -m "<message>"`

- First line should be clear, accurate, and concise
- Use proper spelling, grammar, and punctuation
- Don't end with a `.`

For more advice, see: https://chris.beams.io/posts/git-commit/
