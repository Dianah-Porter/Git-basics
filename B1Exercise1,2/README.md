 #Bundle1 Exercise 1
 
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

  #Bundle1 Exercise 2
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
 104 history
 105 git branch
 106 git switch main
 107 git status
 108 git switch dev
 109 git add .
 110 git commit -m "pushing everything on dev"
 111 git push
 112 git status
 113 git branch
 114 git checkout main