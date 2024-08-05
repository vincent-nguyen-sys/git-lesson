# Git lesson

This lesson covers the basics of git version control.

This lesson is for the first day of the MSSE bootcamp (Chem 280)

1. Make changes to your project that you would like to keep.
2. When you have your changes, tell `git` you are ready to create a checkpocints of the file using the `git add FILENAME` command.
3. create a checkpoint of your file using `git commit -m "Message about what you did"` 
4. View with `git log`, press `q` to get out of the git log.

## Adding features
Features should be developed on brnaches
To create and switch to a branch, use the command

`git switch -c NEW_BRANCH_NAME`

To switch to an existing branch, use

`git switch BRANCH_NAME`