This is team 9506's github practice repository. The concepts demonstrated here
will be:

- The add, commit, push workflow
- How and why you should branch your code
- How merges work
- How pull requests work

Beto was here!

# Cheat Sheet

## The Add/Commit/Push Workflow
- `git status`: run this command to see what files have changed locally on 
    your computer. This will also show you what branch you're currently on.
- `git add <file name>`: run this command to stage changes of local files. Note,
    this does _not_ commit them
- `git commit -m "<a description of your commit>"`: run this command to commit 
    all staged changes. If you haven't staged any changes yet, this command 
    will do nothing. The text you provide after the `-m` flag will be used as 
    a description of your commit, so keep the text short and descriptive.
- `git push origin HEAD`: run this command when you're ready to push your 
    changes to the remote repository so that others can see them
- `git log`: shows you the commit history in your current active branch. Press 
    `q` to exit the log view once you're done here.

## Branching/Pull Requests
- `git checkout -b <name of new branch>`: run this command when you want to 
    create a new branch from the branch you're currently working in. You can
    run `git status` to see what branch you're currently working in.
- Once you've created a branch and are ready to merge it back into your 
  source branch, create a pull request.
