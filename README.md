# Spring Git Workshop
## What I learned
I learned how to connect local and remote repositories using SSH Keys
  218  git config --global user.name "nbarua"
  219  git config --global user.email "galxyglidr@gmail.com"
  220  git config --global core.autocrlf true
  221  git config --global core.autocrlf input
  222  git config --global core.editor "nano"
  223  git config --global init.defaultBranch main
  224  git config --global user.name "nbarua-glitch"
  225  git config --local --global
  226  git config --list --global
  227  mkdir recipes
  228  cd recipes
  229  git init
  230  lis
  231  ls
  232  ls -a
  233  git status
  234  clear
  235  nano guacamole.md
  236  ls
  237  cat guacamole.md
  238  cat guacamole.md 
  239  git status
  240  git add guacamole.md 
  241  git status
  242  git commit -m "Create initial structure for a guacamole recipe."
  243  clear
  244  git status
  245  git log
  246  nano guacamole.md 
  247  nano guacamole.md 
  248  git status
  249  clear
  250  git diff
  251  git commit -m "Ass ingredients for guacamole."
  252  git add guacamole.md
  253  git commit -m "Ass ingredients for guacamole."
  254  git status
  255  nano guacamole.md 
  256  git diff
  257  git add guacamole.md 
  258  git diff
  259  git diff -stages
  260  git diff -staged
  261  git diff --staged
  262  git commit -m "Modify guacamole to the traditional recipe."
  263  git status
  264  clear
  265  git log
  266  git log -2
  267  git log --oneline
  268  nano guacamole.md 
  269  git log
  270  git diff HEAD guacamole.md 
  271  git diff HEAD~1 guacamole.md 
  272  git diff HEAD~4 guacamole.md 
  273  git diff HEAD~2 guacamole.md 
  274  git log
  275  git diff 685318372aa823b4e5712e5baecc685e4d231858 guacamole.md 
  276  git status
  277  git restore guacamole.md 
  278  cat guacamole.md 
  279  git log
  280  git restore -s e1c25d0e8 guacamole.md 
  281  cat guacamole.md 
  282  git restore -s 90a590d7e6a4092 guacamole.md 
  283  cat guacamole.md 
  284  mkdir receipts
  285  touch a.png b.png c.png receipts/a.jpg receipts/b.jpg
  286  ls
  287  git status
  288  nano .gitignore
  289  git status
  290  nano .gitignore
  291  nano .gitignore
  292  git status
  293  nano .gitignore
  294  git status
  295  git commit -m "Ignore png files and receipts folder" receipts/
  296  git commit -m "Ignore png files and receipts folder" recipes/
  297  git add
  298  git add .gitignore
  299  git status
  300  ls -a
  301  git log
  302  nano .gitignore
  303  git add
  304  git add .gitignore
  305  git status
  306  git commit -m "Ignore png files and the receipts folder."
  307  git status
  308  git log
  309  clear
  310  git remote add origin git@github.com:nbarua-glitch/recipes.git
  311  git remote -v
  312  ls -al ~/.ssh
  313  ssh-keygen
  314  ls
  315  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\"
  316  ls
  317  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\"
ls
  318  ls
  319  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\"
  320  ls
  321  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\.pub"
  322  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\.pub"
  323  ls -l
  324  rm ssh-keygen\ -t\ ed25519\ -C\ \"OU\ Libraries\ JupyterHub.pub"
  325  ld
  326  ls
  327  rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\"
  328  rm "ssh-keygen -t ed25519 -C "OU Libraries JupyterHub"
rm "ssh-keygen -t ed25519 -C \"OU Libraries JupyterHub\""
  329  ls -al ~/.ssh
  330  ssh-keygen -t ed25519 -C "OU Libraries JupyterHub"
  331  ls -al ~/.ssh
  332  history
  333  clear
  334  ssh -T git@github.com
  335  cat ~/.ssh/id_ed25519.pub
  336  ssh -T git@github.com
  337  pwd
  338  git push origin main
  339  git push origin main
  340  history
