## Multi-Branch Feature Development and Hotfix Management

1. Feature branches and hotfix branch git log, before merging (changes made in new and common files):
2. Hotfix merge
![1-branches-before-merging-hotfix-merge](./readme-files/1-branches-before-merging-hotfix-merge.png)
3. Rebasing feature-auth (conflict resolutions on app.txt) with push to remote (although rewriting remote history):
![3-rebase-feature-auth-with-push.png](./readme-files/3-rebase-feature-auth-with-push.png)
4. Rebasing feature-dashboard (conflict resolutions on app.txt - reordering commit lines) with push to remote (although rewriting remote history):
![4-rebase-feature-dashboard-with-push.png](./readme-files/4-rebase-feature-dashboard-with-push.png)
5. Merging feature branches into main
   1. FF first branch merge
   2. conflict second branch merge on common app.txt changes
![5-merge-into-main.png](./readme-files/5-merge-into-main.png)
6. Squashing feature branches
7. Resetting main before previous merge and to merge squashed feature branches with remote pushes
![7-main-reset-to-merge-squshed-branches-with-remote-pushes.png](./readme-files/7-main-reset-to-merge-squshed-branches-with-remote-pushes.png)
8. git reflog
![8-git-reflog.png](./readme-files/8-git-reflog.png)