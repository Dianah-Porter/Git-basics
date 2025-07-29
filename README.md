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
-used `git rm --cache README.md` to unstage the changes.
