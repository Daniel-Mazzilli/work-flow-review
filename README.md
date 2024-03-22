# Github Workflow Team Setting

### Reviewing github workflow practices, with the intent to avoid when possible merge conflicts

1. *One team member* **forks** or **creates** a new repo
2. All team members **clone** down the repo to their local machine
3. The owner of the repo proceeds to add their teammates as collaborators.
**On the repo page -> Settings -> Collaborators -> Add people**
4. *Avoid working on the Main branch*, each team member should create their own branch locally

<mark>git checkout -b name-branch</mark> or <mark>git switch -c name-branch</mark>

5. Avoid working on the same files/components simultaneously. Add, Commit, and Push your changes to github
<mark>git push origin name-branch</mark>

6. Coordinate with your team when everyone can merge their branches in succession, and then proceed to pull down the new Main branch.
7. In github and locally delete the branches that were merged.
8. Once the most up to date version of Main was pulled down, proceed to create a new branch locally and continue your work there.
9.** Repeat steps 4-8**