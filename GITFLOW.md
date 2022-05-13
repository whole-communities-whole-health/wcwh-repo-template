# Gitflow

Follow the following steps to work with branching and pull requests in git. These steps are especially useful when multiple people are working in the same repository.

## Set up your repository for editing

1. Clone your repository to your local machine
```
git clone git@github.com:whole-communities-whole-health/YOUR-REPO-NAME.git
```

2. Navigate to the project directory
```
cd YOUR-REPO-NAME
```

3. Add reference (upstream) to the original repository
```
git remote add upstream git@github.com:whole-communities-whole-health/YOUR-REPO-NAME.git
```
Be sure to reference the actual repo name you're using in the commands above

4. Verify the new remote named "upstream"
```
git remote -v
```
Now, checkout your own main branch.

5. Checkout your main branch - you want your new branch to come from the main branch. You are likely already on your main branch, but in case you're not, the following command ensures any new branch you create comes from main.
```
git checkout main
```

## Create a Branch (doing your work)
Whenever you begin work on a new feature or bugfix, it's important that you create a new branch. Not only is it proper git workflow, but it also keeps your changes organized and separated from the main branch so that you can easily submit and manage multiple pull requests for every task you complete.

To create a new branch and start working on it, follow the following steps.

1. Create a new branch (give your branch its own unique informative name)
A suggested branch name is `feature/your_username/` or `feature/your_username/name_of_feature`
If you are fixing a bug, you could use `bugfix/your_username` or `bugfix/your_username/name_of_bug`
It's good practice to include your username in cases where other people may contribute to the same repository.
```
git branch feature/jdoe
```

2. Switch to your new branch
```
git checkout feature/jdoe
```

Now, make the necessary additions and edits that are necessary for your feature or bugfix.

## Submitting your changes (a Pull Request)
Prior to submitting your pull request, you might want to check over your work to make sure everything is as simple and clear as possible. 

1. Add your code to be committed to the repository
```
git add FILENAME(S)
```

2. Add a commit message that briefly describes what you did
```
git commit -m "Your commit message goes here."
```

3. Push your code
```
git push origin name-of-your-branch (i.e. git push origin feature/jdoe)
```

4. Creating a pull request
Once you've committed and pushed all of your changes to GitHub, go to the repo page on GitHub, select your development branch, and click the green "Compare & pull request" button. On the next screen, click "Create pull request," and finally "Merge pull request."

 If you need to make any adjustments to your pull request, just push the updates to GitHub. Your pull request will automatically track the changes on your development branch and update.