Git basics:

- Created a new folder and initialized git using `git init` which creates a hidden folder that git stores information needed to track files.

- Made changes to the folder and added `index.html` and `README.md` files and added the contents as well.
- used `git status` to see the files if are tracked or not before commit this is the result:
    On branch master
    No commits yet
    Untracked files:
    (use "git add <file>..." to include in what will be committed)
            README.md
            index.html

    nothing added to commit but untracked files present (use "git add" to track)

- used `git add README.md`to stage the README.md file inorder to be included in next commit(snapshot);
- Used `git restore --staged README.md` to unstage the changes.
- Used `git add .` to add all files 
- Used `git status`
    On branch master
    No commits yet
    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   index.html

- Applied ` git commit -m "Added index.html  file"` to save the staged files permanently
- `git restore README.md` to discard changes in the working directory.
- `git log ` to see commit history
- Added a tag `git tag v1.0` and deleted  it using `git tag -d v1.0`
