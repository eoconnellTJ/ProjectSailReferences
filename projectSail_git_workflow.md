# Project Sail: Issue Workflow

Once you are assigned a task on Jira, you will have a specific commit procedure to keep the project history organized.

## Jira issue numbers

Your tasks will have issue numbers, which you will use to name the git branch that you will resolve the issue on:

#### Example
If the issue number for the task is, for example, ```PS-9```, you will have to ```git checkout -b PS-9``` in order to create and switch to the new branch for the issue.

Whenever you ```git commit```, start the commit messages with ```PS-9```:

```shell
git commit -m "PS-9 {add a relevant message here}"
```

> if git prompts you to ```git push --set-upstream origin PS-9``` upon pushing the commits to remote, go ahead and do so.

These should trigger changes in Jira that move issues from ```OPEN``` to ```IN PROGRESS```, and the commits should be tracked to the issue as well.

![JiraIssues](/JiraIssues.png)
