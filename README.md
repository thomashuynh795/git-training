create a new branch
- `git checkout -b <new branch name>`

check commit history on a branch
- `git log`

rebase a commit on a branch
- `git pull --rebase`
- `git add .`
- `git commit -m <message>`
- `git push`

rebase 2 branches
- `git checkout <branch you will delete>`
- `git rebase <branch name we want to rebase in>`
- resolve conflits
- `git add .`
- `git rebase --continue` or `git rebase --skip`
- `git checkout <branch we want to merge in>`
- `git merge <branch name we want to merge>`
- `git push`

delete a branch
- `git push origin --delete <branch to delete>`