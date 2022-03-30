# Gitflow

## Clone your repository to your local machine
```
git clone git@github.com:USERNAME/FORKED-PROJECT.git
```

## View all branches, including those from upstream
```
git branch -v
```
Now, checkout your own main branch:

## Checkout your main branch
```
git checkout main
```

**Create a Branch** (doing your work)
Whenever you begin work on a new feature or bugfix, it's important that you create a new branch. Not only is it proper git workflow, but it also keeps your changes organized and separated from the master branch so that you can easily submit and manage multiple pull requests for every task you complete.

To create a new branch and start working on it, peform the following flow.

## Checkout the main branch - you want your new branch to come from main
```
git checkout main
```

## Create a new branch (give your branch its own simple informative name)
For enhancements use `feature/your_username/issue#` or `feature/your_username/name_of_feature`

For bugs use `bug/your_username/issue#` or `bug/your_username/name_of_bug`

```
git branch feature/jdoe/567
```

## Switch to your new branch
```
git checkout feature/jdoe/567
```
Now, go to town hacking away and making whatever changes you want to.

## Submitting your changes (a Pull Request)
Prior to submitting your pull request, you might want to do a few things to clean up your branch and make it as simple as possible for the original repo's maintainer to test, accept, and merge your work.

In the time that you've been working on your changes, if any commits have been made to the upstream master branch, you will need to rebase your development branch so that merging it will be a simple fast-forward that won't require any conflict resolution work.


## Add your code
```
git add FILENAME
git commit -m "Your commit message goes here."
```

## Push your code
```
git push origin name-of-your-branch
```

## Submitting
Once you've committed and pushed all of your changes to GitHub, go to the repo page on GitHub, select your development branch, and click the pull request button. If you need to make any adjustments to your pull request, just push the updates to GitHub. Your pull request will automatically track the changes on your development branch and update.
