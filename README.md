# commit-rules

# The commit type can be
* feat: Commits, which adds a new feature
* fix: Commits, that fixes a bug
* refactor: Commits, that rewrite/restructure your code, however, do not change any behavior
* perf: Commits are special refactor commits, that improve performance
* style: Commits, that do not affect the meaning (white space, formatting, missing semi-colons, etc)
* test: Commits, that add missing tests or correct existing tests
* docs: Commits, that affect documentation only
* build: Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
* chore: Miscellaneous commits e.g. modifying .gitignore

# first rule:
Only one type per commit

# second rule:
The commit scope can be
A scope MUST consist of a noun describing a section of the codebase surrounded by parenthesis.

// for example 
git commit -m "feat(profile): add button for update call"

# third rule:
Linking to Jira: Writing the number of the task that was solved

// for example 
git commit -m "(JIRA-231) feat (dashboard): add sign-out button"

# fourth rule:
To get atterntion for important code you should: Commit message with ! to draw attention to breaking change

// for example 
git commit -m "feat!: send an email to the customer when a product is shipped"

# fifth rule:
Message should be in present not past 

// for example 
git commit -m "refactor:change the text"git commit -m "refactor:change the text"✅
git commit -m "refactor:changed the text"
