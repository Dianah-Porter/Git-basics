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
- `git reset --soft HEAD~1` 
 2 cd ..
   3 cd Git
   4 git status
   5 git add .
   6 git restore
   7 git add .
   8 git commit -m "Bundle 1 Exercise 1"
   9 git status
  10 git remote add origin https://github.com/Dianah-Porter/Git-basics.git
  11 git push origin dev
  12 git switch main
  13 git stash
  14 git git stash show
  15 git stash show
  16 git stash clear
  17 git stash show
  18 git stash push -m "gitstash on home.html"
  19 git stash push -m "stash2 on about.html"
  20 git stash show
  21 git stash list
  22 git add about.html
  23 ls
  24 cd B1 Exercise1,2
  25 cd B1 Exercise1,2
  26 git stash list
  27 git stash apply stash@{0}
  28 git stash apply
  29 git add .
  30 git commit --no-edit
  31 git commit -m "Bundle 1 Exercise1"
  32 git remote add origin https://github.com/Dianah-Porter/Git-basics.git
  33 git push origin dev
  34 git status
  35 git add home.html
  36 git stash push -m "stash1 on home.html"
  37 git stash push -m "stash1 on home.html" -u
  38 git stash list
  39 git stash drop stash@{1}
  40 git stash list
  41 git stash clear
  42 git stash list
  43 git stash push -m "stash1 on home.html"
  44 git stash push -m "stash1 on home.html" -u
  45 git stash push -m "stash1 on home.html" -u
  46 git stash list
  47 git stash push -m "stash2 on about.html" -u
  48 git stash list
  49 git stash push -m "stash3 on team.html" -u
  50 git stash list
  51 git stash pop stash@{1}
  52 git stash pop 'stash@{1}'
  53 git stash pop 'stash@{2}'
  54 git stash list
  55 git stash pop 'stash@{1}'
  56 git add .
  57 git commit -m "Applied and stashed on about and home files"
  58 git status
  59 git remote add origin https://github.com/Dianah-Porter/Git-basics.git
  60 git push origin main
  61 git push origin dev
  62 git add .
  63 git status
  64 git commit -m "modified README with stash commands"
  65 git push origin dev
  66 git status
  67 git stash list
  68 git stash pop 'stash@{0}'
  69 git reset
  70 git status
  71 git history
  72 git reset --hard HEAD~2
  73 git status
  74 history
  75 git pull origin dev
  76 git status
  77 git log
  78 git reset --soft HEAD~1
  79 git log
  80 git add .
  81 git commit -m "using git reset"
  82 git push origin dev
  83 git pull origin dev
  84 git push origin dev
  85 git add B1Exercise1,2/README.md
  86 git commit -m "removed conflicts"
  87 git push origin dev
  88 git add B1Exercise1,2/README.md
  89 git commit -m "Modified README.md"
  90 git diff
  91 git diff --staged
  92 git log
  93 git log --online
  94 git log --oneline
  95 git diff
  96 git diff 02d658a
  97 git log --graph
  98 git help
  99 git help branch
 100 git branch --help
 101 git help --all
 102 git checkout -b 'ft/bundle-2'
 103 git status