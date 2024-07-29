# commit-rules

# The commit type can be
feat: Commits, which adds a new feature
fix: Commits, that fixes a bug
refactor: Commits, that rewrite/restructure your code, however, do not change any behavior
perf: Commits are special refactor commits, that improve performance
style: Commits, that do not affect the meaning (white space, formatting, missing semi-colons, etc)
test: Commits, that add missing tests or correct existing tests
docs: Commits, that affect documentation only
build: Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
ops: Commits, that affect operational components like infrastructure, deployment, backup, recovery...
chore: Miscellaneous commits e.g. modifying .gitignore

# first rule:
Only one type per commit

# second rule:
The commit scope can be
A scope MUST consist of a noun describing a section of the codebase surrounded by parenthesis.

// for example 
git commit -m "feat(profile): add button for update call"


