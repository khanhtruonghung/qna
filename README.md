# qna

aa




This repo is use for learning golang


### Question about Squash commit in Git:

- You will use squash commit a lot because it make your git flow more organize or you can change the commit message.

- Command to use squash commit: `$ git rebase -i [branch name]`

- After that change all the `pick` on each commit to `squash or s` except the first one. All the change on your code won't lost but you can change the message are a collection of all commit message were changed to `squash`

- Finaly, using squashed commit `$ git push -f` to overwrite the newest commit with the oldest commit.
