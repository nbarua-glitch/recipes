# Spring Git Workshop
## What I learned
I learned how to connect local and remote repositories using SSH Keys
    1  pwe
    2  pwd
    3  ls
    4  pwd /home/joyvan
    5  ls
    6  pwd/home/joyvan
    7  ls
    8   pwd /home/joyvan
    9  ls
   10  pwd
   11  ls
   12  pwd /home/joyvan
   13  ls
   14  cd swc_workshop
   15  cd swc_workshop
   16  pwd
   17  wget https://github.com/oulib-swc/ou_swc_files/archive/master.zip
   18  unzip master.zip
   19  ls -F
   20  wget https://swcarpentry.github.io/shell-novice/data/shell-lesson-data.zip
   21  unzip shell-lesson-data.zip
   22  ls -F
   23  ls -l
   24  unzip shell-lesson-data.zip
   25  y
   26  ls -F
   27  ls -F shell-lesson-data
   28  ls -F exercise-data
   29  ls -F shell-lesson-data/exercise-data
   30  ls -F shell-lesson-data/exercise-data/creatures
   31  ls -F shell-lesson-data/exercise-data/creatures
   32  pwd
   33  cd shell-lesson-data/exercise-data/creatures
   34  pwd
   35  cd
   36  pwd
   37  ls -F
   38  cd swc_workshop
   39  ls -F
   40  cd shell-lesson-data/exercise-data/
   41  pwd
   42  ls -aF
   43  cd ..
   44  pwd
   45  ls -aF
   46  cd ../../..
   47  ls
   48  ls -F
   49  cd -
   50  cd ../..
   51  pwd
   52  cd -
   53  cd swc_workshop
   54  ls -F
   55  cd exercise-data/alkanes/
   56  ls -aF
   57  pwd
   58  cd ../..
   59  pwd
   60  cd exercise-data/alkanes/
   61  cd ../../..
   62  cd -
   63  cd ../../../.
   64  ls -F
   65  cd -
   66  cd ../../..
   67  cd -
   68  touch "shell data"
   69  ls -Fl
   70  cd ./
   71  pwd
   72  cd .
   73  ls -aF
   74  cd .
   75  cd ./
   76  cd ../
   77  cd -
   78  ls -aF
   79  rm "shell data"
   80  ls -aF
   81  rm -i propane
   82  rm -i propane.pdb
   83  ls -aF
   84  cd ../../..
   85  ls -Fl
   86  cd .
   87  cd -
   88  cd -
   89  cd shell-lesson-data/exercise-data/alkanes/
   90  rm -i shell-lesson-data.zip
   91  cd ../../..
   92  rm -i shell-lesson-data.zip
   93  cd -
   94  cd ../../..
   95  ls -Fl
   96  rm -i ou_swc_files-master
   97  mkdir thesis
   98  ls -F
   99  ls
  100  nano epic.txt
  101  nano epic.txt
  102  nano epic.txt
  103  ls -lh
  104  cat epic.txt
  105  cd /usr/bin
  106  ls -aF
  107  ls -aF | less
  108  less
  109  less gs*
  110  man
  111  man ls
  112  cd -
  113  man ls
  114  unminimize
  115  ls --help
  116  ls -aF
  117  cd shell-lesson-data/exercise-data/
  118  mv exercise-data thesis/
  119  cd exercise-data/
  120  pwd
  121  ls
  122  mv numbers.txt thesis/
  123  mv numbers.txt ../../thesis/
  124  cd /thesis
  125  cd
  126  ls -aF
  127  cd home
  128  cd home/
  129  cd swc_workshop
  130  ls -aF
  131  cd thesis/numbers.txt 
  132  cd thesis/
  133  ls
  134  ls -aF
  135  cd ..
  136  mkdir backups
  137  cp numbers.txt
  138  cd -
  139  cp numbers.txt
  140  cd ..
  141  cp numbers.txt backups/
  142  cd -
  143  cp numbers.txt backups/
  144  cp numbers.txt
  145  cp numbers.txt jobo.txt
  146  ls
  147  cp numbers.txt backups/jobo.txt
  148  mv jobo.txt ../backups
  149  ls
  150  cp numbers.txt ../backups/jobo.txt
  151  cd ../backups
  152  ls -aF
  153  rm jobo.txt
  154  cp numbers.txt ../backups/jobo.txt
  155  cd -
  156  cp numbers.txt ../backups/jobo.txt
  157  cd -
  158  ls
  159  cd ..
  160  cd shell-lesson-data/exercise-data/alkanes/
  161  wc cubane.pdb
  162  ls *pdb
  163  wc -l *pdb
  164  wc *pdb
  165  wc -l *pdb > length.txt
  166  ls
  167  sort length.txt
  168  sort -n length.txt
  169  wc -w *pdb > length.txt
  170  wc -w *pdb
  171  wc -w *pdb > length.txtls -aF
  172  ls -aF
  173  sort length.txtls
  174  sort length.txt
  175  echo joe
  176  wc -w *pdb | ls | head -1
  177  wc -w *pdb | sort -n | head -
  178  cd ..
  179  ls -aF
  180  cd animal-counts/
  181  ls -aF
  182  cat animals.csv 
  183  uniq animals.csv 
  184  cut -d, -f 2 animals.csv 
  185  cat animals.csv 
  186  cut -d, -f 2 animals.csv | sort | uniq
  187  pwd
  188  cd ..
  189  ls -aF
  190  cd alkanes/
  191  nano sort.sh
  192  nano sort.sh
  193  bash sort.sh
  194  cd creatures
  195  cd ..
  196  cd creatures/
  197  ls
  198  for item in basilisk.dat minotaur.dat ; do head -n 2 $item | tail -n 1; done
  199  cat basilisk.dat 
  200  head basilisk.dat 
  201  for dog in *.pdb; do head -n 2 $dog | tail -n 1; done
  202  for dog in *dat; do head -n 2 $dog | tail -n 1; done
  203  for dog in *dat; do head -n 2 $dog | tail -n 1; done
  204  for class in *dat; do head -n 2 $class | tail -n 1; echo "*******"; done
  205  history
  206  history less
  207  history less
  208  history ls
  209  history
  210  history | less
  211  ls --help
  212  cd ..
  213  ls -F
  214  cd data
  215  ls -F
  216  pwd
  217  pwd
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
