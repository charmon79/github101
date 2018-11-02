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