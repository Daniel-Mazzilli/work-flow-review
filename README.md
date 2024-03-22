# Github Workflow Team Setting

### Reviewing github workflow practices, with the intent to avoid when possible merge conflicts

1. *One team member* **forks** or **creates** a new repo

2. All team members **clone** down the repo to their local machine

3. The owner of the repo proceeds to add their teammates as collaborators, **on the repo page -> Settings -> Collaborators -> Add people**

4. *Avoid working on the Main branch*, each team member should create their own branch locally: `git checkout -b name-branch` or `git switch -c name-branch`

5. Avoid working on the same files/components simultaneously. Add, Commit, and Push your changes to github: `git push origin name-branch`

6. Coordinate with your team when everyone can merge their branches in succession, and then proceed to pull down the updates merged on the Main branch, `git pull origin main`

7. In github and locally delete the branches that were merged. In your terminal move to a different branch from the one you want to delete: `git checkout name-branch` or `git switch name-branch` Delete command: `git branch -d name-branch` if you try to delete locally before you pulled down the updated main you will need to use the command `git branch -D name-branch`

8. Once the most up to date version of Main was pulled down, proceed to create a new branch locally and continue your work there. **See steps 4-7**