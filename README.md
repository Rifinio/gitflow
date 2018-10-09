# Git branch to show how to use gitflow

In order to use gitflow as explained in this article https://nvie.com/posts/a-successful-git-branching-model/ i created this repositoy.

The main issue that is happening with projects trying to adopt the gitflow on github is which option to use when merging pull requests `create a merge commit`, `Squash and merge` or `Rebase and merge`.

and the answer to this is to use `create a merge commit` only in the case of `hotfix` or merging a `release` branch into `master` and `develop`


On `feature` and `tasks` and when trying to merge back to `develop` the `Rebase and merge` option should be used.

