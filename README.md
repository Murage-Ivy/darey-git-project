# darey-git-project
#### Create a index.txt file using 
```touch command```

#### Staged the file using `git add .`

#### Commited the file using `git commit -m <message>`

![Staging and committing](./images/Screenshot%20from%202023-10-04%2017-26-49.png)

* Created a new branch using 
```
git checkout -b <branchname>
```
* Listed all available branches using
```
git branch
```
* Switch to another branch using
```
git checkout <branchname>
```
![Create and switch to an old branch](./images/Screenshot%20from%202023-11-01%2022-44-12.png)


#### Merge a branch into another branch
* First, you need to be on the branch from which you want to merge (let's call it `master`). Use:
```
git merge <branchname>
```
![Merge master into main](./images/Screenshot%20from%202023-11-01%2022-47-09.png)

#### Delete an old branch
* You can delete a local branch with this command:
```
git branch -d <branchname>
```
![Delete master branch](./images/Screenshot%20from%202023-11-01%2022-50-15.png)


#### Pushed my local reposirtoy to the remote repository
* To push your changes to GitHub, use the following commands in order:
* Add all files that have been modified or added since the last commit by running `git add .`
* Then commit those changes by running `git commit -m "Your detailed message here"`.
* Finally, push the changes to the remote repository with `git push origin <your_current_branch>`

![Push the repository](./images/Screenshot%20from%202023-11-01%2022-51-51.png)