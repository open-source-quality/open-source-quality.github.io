# 2018-02-15. Time writing. Open OSS Quality Evaluation Spec
## Intro

Previously, I talked much about problems we have while not enough about data and algorithms.

I suggest to move from the available _Data Sources_ to the _Data Available_ and then to the possible _Metrics_,
based on combination of available data series.

Let's start.

## Types of Data Source

What kind of _Data Sources_ will I consider?
Possible list source types:
- Bug\Task Tracking Systems (GitHub\GitLab...)
- Version Control Systems (git, svn)
- Package Management System (Rubygems, NPM)
- Documentation\WiKi Storage Systems (postrgres docs)
- Source Code (also tests, examples and part of docs here)

## Bug\Task Tracking Systems Data
### Participants:
  - Type (bug reporters, commenters, contributors, watchers, stargazers...)
  - Name
  - Actions for Time Frame: create issue/pr, comment, star, watch, fork
### Issues
  - Title
  - Description
  - Actions for Time Frame: open, comments, close
### PRs
  - Title
  - Description
  - Actions for Time Frame: open, close, merge, commits, changes, approved, checks passed?
### "Projects"
  - Tasks
  - Actions for Time Frame: task create, finish, other state
### Branches
  - Name
  - Actions for Time Frame: default?, commits, contributors, create, delete
### Tags
  - Name
  - Actions for Time Frame: create, name based type (SymVer), tagger (+ email)
### Forks
  - Actions for Time Frame: create, remove, changes?
### Wiki
  - Actions for Time Frame: changes in size, exists
### License
  - Actions for Time Frame: exists, valid?
### Commits
  - Owner
  - Name
  - Description
  - Amount of changes
  - Issues Links

## Version Control Systems Data
### Contributors
  - Name
  - Actions for Time Frame: number of commits, new?, name
### Branches
  - Actions for Time Frame: default?, commits, contributors, create, delete
### Tags
  - Actions for Time Frame: create, name based type (SymVer), tagger (+ email)
### Commits
  - Owner
  - Name
  - Description
  - Amount of changes
  - Files changes
  - Patch...

## Package Management System
### Packages
  - Authors
  - Owners
  - Releases
  - Downloads
### Authors
  - Name
### Owners
  - Name
### Releases
  - Name
  - Date
  - Downloads
  - Dependencies
  - Reverse Dependencies
### Dependencies
  - Package name
  - Development\Runtime
  - Version Locks
### Reverse Dependencies
  - Package name
  - Version Locks

## Documentation\WiKi Storage Systems
What am I able to collect here? The format is unpredictable... Only scrapping the `html` which
does not make sense...

Actually, I have to create a knowledge map here. Kind of stats about different types of docs.

__Need some insight here.__

## Source Code
### Source Documentation (inc. README)
### Process Documentation (CONTRIBUTING.md, ...)
### Tests
### Examples
### License
### Source Processing Tools (deps, package meta, installer, CI, linters, ...)
  - Dependencies lock
  - Package meta
  - Installer
  - Tests/Linters runner
  - Linters configuration
  - CI\CD configuration
  - Container configuration
### Implementation Source Code
  - Language (file extension based)
  - Size
  - Content (object of Linters and Static Analysis)
### Assets (images, PDFs, ...)
  - Type
  - Size
