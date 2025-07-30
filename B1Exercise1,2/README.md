Git basics:

- Created a new folder and initialized git using `git init` 
- Made changes to the folder and added `index.html` and `README.md` files and added the contents as well.
- used `git add README.md`to stage the README.md file inorder to be included in next commit(snapshot);
- Used `git restore --staged README.md` to unstage the changes.
- Used `git add .` to add all files 
- Applied ` git commit -m "Added index.html  file"` to save the staged files permanently
- `git restore README.md` to discard changes in the working directory.
- `git log ` to see commit history
- Added a tag `git tag v1.0` and deleted  it using `git tag -d v1.0`
- `git branch -m main ` to rename from master to main
- `git remote add origin main https://github.com/Dianah-Porter/n.git` 
- `git push -u origin main` to push to main branch.
- `git checkout -b dev` to create and switch
- `git branch dev` && `git checkout dev` to switch to it
- `git switch -c test`
- `git branch -d test` to delete branch test.

Exercise 2:

- `git stash` // to create a stash
- `git stash push -m "stah 3" -u`   // to stash the untracked file
- `git stash list` // shows a list of stashes like:													
- `git stash drop 'stash@{0}'`	// to delete a specific stash 
- `git stash clear` // to delete all stashes 
- `git stash apply 'stash@{1}'`