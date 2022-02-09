![](https://i.imgur.com/5J85Qir.png)

# Github Basics Exercise

###### tags: `Github` `Git` `Workflow` `Basics`


This exercise helps to use `Git` and `Github`. You can also find some helpful git commands below.

> :bulb: Some useful git commands,
> 
>  * git remote or git remote -v to view / display any existing remotes for our repo.`git remote add <name> <url>` to add new a remote
>  * To clone a repo ,  `git clone <url>`. Make sure that you are not inside of a repo when you clone !
>  * `git diff HEAD [filename]`
>  * `git diff --staged [filename]`
>  * `git diff branch1..branch2`
>  *  `git stash pop` to remove most recent stashed changes into your stash adn re apply them to your working copy.
>  *  `git stash` to hide them but remembers them 
>  *  `git stash save`  they save your current staged or unstaged changes
>  *  `git stash` provides an easy  way of stashing these uncommitted changes so that we can return to them later, without having to make  unnecessary commits.
>  *  `git stash apply` that you can apply whatever stashed away, without removing it from the stash
>  *  `git stash drop <stash-id>` to delete particular stash.
>  *  `git reset <commit-hash>` will reset the repo back to a specific commit.
>  *  `git restore --staged <filename>` to unstage staged file in thje commit that you don't want to stage it.
>  *  `git reset --hard <commit-hash>` to lose commits git upto this commit hash ,so changes are gone.
>  *  `git revert <commit-hash>`
>  *  git revert is similar to git reset , they both UNDO changes
>  * git reset actually moves the branch pointer backwards, eliminating commits
>  * git revert creates a brand new commit which reverses/undos the change from a commit. Because it results in a new commit, you will be prompted to enter a commit message.----> commit still there but changes are undo


:rocket: 
---


## :memo: Where do I start?

## Step # 1
Create a new repository locally on your machine.
## Step 2
Create a new Github repository.
## Step 3
Connect your local repo to the Github repo.
## Step 4
Change the name of the default branch from master to main.
## Step 5
Make a new file called `favorites.txt`. Leave it empty. 
## Step 6
Make your first commit on the `main` branch. 
## Step 7
Push up your `main` branch to Github! Make sure you see your empty `favorites.txt` file on Github.
## Step 8
Create two branches: `foods` and `movies`
## Step 9 
Switch to the `foods` branch. Add three (or more) of your favorite foods to the `favorites.txt` file. Add and commit your changes on the `foods` branch.
## Step 10
Switch to the `movies` branch and add three or more of your favorite movies to the `favorites.txt` file. Add and commit your changes on the movies branch.
## Step 11
Push up your `foods` branch to Github. Make sure you see it on Github!
## Step 12
Push up your `movies` branch to Github. Make sure you see it on Github!
## Step 13
Merge the `foods` branch into the `main` branch. Then merge the `movies` branch into the `main` branch. If necessary, resolve conflicts so that you end up with your favorite foods and favorite movies in the same `favorites.txt` file. 
## Step 14
Push the most delinquent work upon your `main` branch to Github.