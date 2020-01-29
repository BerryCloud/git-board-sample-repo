# GitBoard sample repository

Provides a repository with reasonable data and history to be able to test and demo *GitBoard*.

## Git history

Git history to emulate different valid states of issues.

```
* issue #896                            → done
| * commit (tag: custom-tag)
| * commit with fix of issue #977       → in progress
| branch-without-number
|/
| 895-issue-fix-branch: no commits      → in progress
|/
* issue #870                            → done
* issue #901                            → done
| * commit for issue #894               → in progress; ❗️ not selected
| branch-without-number
|/
| 791-issue-branch: no commits          → in progress
|/
* issue #895
* issue #715                            → done; ❗️ not selected
* issue #977
* issue #575                            → done
* issue #412 (tag: v3.0)                → released (in v3.0)
* issue #153                            → released (in v3.0)
* issue #209                            → released (in v3.0)
* issue #959                            → released (in v3.0)
* issue #411                            → released (in v3.0)
* issue #389                            → released (in v3.0)
* issue #432                            → released (in v3.0)
* issue #334                            → released (in v3.0)
* issue #293                            → released (in v3.0)
* issue #107                            → released (in v3.0)
* issue #281                            → released (in v3.0)
* issue #253                            → released (in v3.0)
* issue #210 (tag: v2.1)                → released (in v2.1)
* issue #635 (tag: v2.0)                → released (in v2.0)
* issue #459                            → released (in v2.0); ❗️ not selected
* fix of issue #725 (tag: v1.0)         → released (in v1.0)
* issue #725                            → released (in v1.0)
* issue #613                            → released (in v1.0)
|
master branch
```

change for GB-979
