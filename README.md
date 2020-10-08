# DATA STRUCTURE AND ALGORITHM QUESTIONS
It contains different type of questions from different topic with proper describing of the better solution.You will here find the best solution for any dsa question.

## Index



## Getting Started :scroll:

### 1. Fork it :fork_and_knife:

Get a fork/copy of this repository by clicking on <a href="https://github.com/Jaidev2001/DSA-Q/fork"><kbd><b>Fork</b></kbd></a> button.

[![Fork Button](https://upload.wikimedia.org/wikipedia/commons/3/38/GitHub_Fork_Button.png)](https://github.com/Jaidev2001/DSA-Q/fork)

### 2. Clone it :busts_in_silhouette:

Clone it into your local PC by using

```sh
$ git clone https://github.com/Jaidev2001/DSA-Q
```

> This command creates a copy of this repository in your machine.

After cloning this repository, move into this repository by using

```sh
# This will change directory to Sorting-Algorithm
$ cd DSA-Q/
```

### 3. Setting up :arrow_up:

Below are the following commands to see your *local copy* has a reference to your *forked repository* in Github :octocat:

```sh
# Here YourUserName is your Github User name
$ git remote -v
origin	https://github.com/YourUserName/DSA-Q.git (fetch)
origin	https://github.com/YourUserName/DSA-Q.git (push)
```

Add reference to this repository by using

```sh
$ git remote add main https://github.com/Jaidev2001/DSA-Q
```

> This command adds a new remote named **main**.

To see the changes, run the following command

```sh
$ git remote -v
main	https://github.com/Jaidev2001/DSA-Q.git (fetch)
main	https://github.com/Jaidev2001/DSA-Q.git (push)
origin  https://github.com/YourUserName/DSA-Q.git (fetch)
origin  https://github.com/YourUserName/DSA-Q.git (push)
```

### 4. Synchronize :recycle:

Always make sure to update your local repository with this repository before making any changes.

```sh
# Fetch all remote repositories & delete any deleted remote branches
$ git fetch --all --prune

# Switch to `master` branch
$ git checkout master

# Reset local `master` branch to match `main` remote repository's `master` branch
$ git reset --hard main/master

# Push changes to your forked `DSA-Q` repository
$ git push origin master
```

Now you are ready to start contributing and sending pull requests.

## Contribute

You are freely welcome to send a pull request on any sorting algorithm, typo correction, bug. Your contribution will be highly appreciable :thumbsup:. When you want to contribute to this repository then create a another branch and send a [new pull request](https://github.com/Jaidev2001/DSA-Q/compare?expand=1) here.

Create an another branch for contribution.

```sh
# This will create a new branch `new` & switch to `new` branch
$ git checkout -b new
```

To add your changes to the branch

```sh
# To add all your files to branch `test`
$ git add .
```

Commit a new info or message for your changes

```sh
# This message will show in your all files that you have changed
$ git commit -m 'message or info for your changes'
```

Push your changes to your remote repository

```sh
# To push your changes to your remote repository in test branch
$ git push -u origin new
```

Voila !!! Then head towards to your repository in any browser and click on `compare and pull requests`. Then add a title & description to your pull request that explains what you have done.

## Tech/Framework Used
+ [GCC](https://gcc.gnu.org/) compiler
+ [VSCODE](https://code.visualstudio.com/) (A source code editor)

## Credits
+ [GeeksforGeeks](https://www.geeksforgeeks.org/)
