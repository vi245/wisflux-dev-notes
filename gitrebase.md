# How to Rebase

When you made some commits on a feature branch (test branch) and some in the master branch. You can rebase any of these branches. Use the git log command to track the changes (commit history). Checkout to the desired branch you want to rebase. Now perform the rebase command as follows:

Syntax:

`$git rebase <branch name>`

If there are some conflicts in the branch, resolve them, and perform below commands to continue changes:

`$ git status `

It is used to check the status,

`$git rebase --continue`

The above command is used to continue with the changes you made. If you want to skip the change, you can skip as follows:

`$ git rebase --skip `
When the rebasing is completed. Push the repository to the origin. Consider the below example to understand the git merge command.
