## Getting started

### Clone this repository
```git clone https://github.com/charmon79/github101.git```

This will create the directory `github101` in your current working directory, and pull down all of the files in the repository to that directory.

### Change directory to the cloned repo directory
```cd github101```

### Set your identity within the repository.
This will be used when you do commits, to tell other people who made the commits.

```git config user.email "you@example.com"```
```git config user.name "Your Name"```

### Create a new branch
```git branch your-branch-name```

### Switch to new branch "foo"
```git checkout your-branch-name```

### Create a new file in the directory
This can be anything you like. I'd recommend a simple text file for now.

### Stage your changes. For now, we'll just stage all changes in the directory to keep the demo simple.
```git add .```

### Commit your changes, with a commit message describing your changes.
```git commit -m "I changed stuff"```

### Push your branch with your changes to the GitHub copy of this repository
```git push --set-upstream origin your-branch-name```

### Open a pull request on your branch
Easiest way to do this is through the GitHub website.

A Pull Request lets others review & comment on your changes, and also provides an easy way for approved users to merge your changes into the base branch.

### After you're done with your branch, delete it
Maybe you had your branch's changes merged into another branch. Maybe you want to throw away your changes & start over. Either way, you'll want to delete your branch.
```git branch -b your-branch-name```

*Note: You'll need to be standing on a different branch first.*

### Pull the master/trunk branch to get latest changes from remote to your local copy
Pull early, pull often. Pull ALL THE TIME.

Before you create a new branch from master, ALWAYS pull the latest from master.
```git checkout master```
```git pull```

It's also a best practice to regularly pull master (or whatever your trunk branch is) and merge its latest changes into your current working branch. This lets you detect merge conflicts in your branch, *before* trying to merge your changes back to the trunk.