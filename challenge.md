# Afternoon Challenge

## Create a Repo
1. Create a new folder on your computer "git-test"
2. Initialize the git repo using `git init`
3. Create a file in here called `README.md` and paste the following text in there

```
Lorem Ipsum is simply dummy text of the printing and typesetting

 industry. Lorem Ipsum has been the industry's standard dummy text

ever since the 1500s, when an unknown printer took a galley of

type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into 

electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets 

containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of

Lorem Ipsum
```

4. On github, create a new repository called "git-test-remote"
5. Copy and paste the `git remote add origin [url]` command into your terminal to connect the local repo to the remote one.
6. Add, commit and push your local changes to the remote repository.

## Clone the repo
1. In a separate folder on your computer "git-test-2" (or whatever you want to name it) clone the `git-test-remote` repo using the URL provided by github (Don't put this folder in the original `git-test` folder)
2. Remove the first line of README.md then add, commit and push your changes to remote master

## Merge Conflicts
3.  Go back into the original "git-test" folder (the repo we made first), and remove the last 2 lines of README.md (DO NOT git pull first, we're trying to simulate a merge conflict).
4.  Add, commit and try to push your changes to master, you should get an error. 
5. Now git pull and resolve the merge conflicts
6. Git add and commit the merged changes
7. Push to the repo

## Forking
8. Fork this github repo
9. Clone the fork to your local machine
10. Create a branch called [name]-challenge-branch
11. Add your name to the README
12. Add, commit and push your changes to the new branch
   
13. In the people folder, create a file called [name]-info.md
14. Put a link to your github account in here
15. Add, commit and push your changes to your branch

16. Finally open a PR and ask to merge your new branch into the original repository
