    1  history
    2  clear
    3  echo $fullname
    4  exit
    5  echo $fullname
    6  export fullname="ali mustafa"
    7  echo $fullname
    8  exit
    9  echo $fullname
   10  exit
   11  fullname="sara mostafa"
   12  echo $fullname
   13  bash
   14  echo $fullname
   15  export fullname
   16  bash
   17  echo $fullname
   18  bash
   19  man bash
   20  ls
   21  pwd
   22  clear
   23  pwd
   24  sudo useradd sara -c "sara mostafa" -m
   25  sudo passwd sara
   26  sudo useradd baduser -c "Bad User" -m 
   27  sudo passwd baduser
   28  ls -l
   29  ls ..
   30  pwd
   31  cat /etc/passwd
   32  tail -n 3 /etc/passwd
   33  groupadd -g 30000 pgroup
   34  sudo groupadd -g 30000 pgroup
   35  ls ..
   36  getent group pgroup 
   37  sudo groupadd -g badgroup 
   38  sudo groupadd badgroup 
   39  cat /etc/groups
   40  cat /etc/group
   41  sudo usermod -a -G sara pgroup
   42  sudo usermod -a -G pgroup sara
   43  getent group pgroup
   44  sudo passwd sara
   45  ls ..
   46  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara1
   47  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara
   48  sudo chage --expiredate $(date -d +30days +%Y-%m-%d) sara
   49  sudo passwd -1 baduser 
   50  sudo passwd -l baduser 
   51  sudo deluser baduser
   52  ls ..
   53  sudo deluser --remove-home baduser
   54  ls .. 
   55  cat /etc/passwd |grep baduser
   56  sudo rm -rf /home/baduser
   57  ls ..
   58  pwd
   59  sudo groupdel badgroup 
   60  tail -n 5 /etc/group
   61  cd 
   62  pwd
   63  cd .. 
   64  pwd
   65  touch myteam 
   66  cd ubuntu
   67  pwd
   68  sudo passwd ubuntu 
   69  cd ..
   70  mkdir myteam
   71  mkdir ~/myteam
   72  ls 
   73  pwd
   74  cd /myteam
   75  cat |grep myteam
   76  cd .. 
   77  ls
   78  cd home
   79  ls
   80  sudo mkdir myteam
   81  ls
   82  chmod ugo+r myteam
   83  sudo chmod ugo+r myteam
   84  sudo chmod ugo-r myteam
   85  cd ubuntu
   86  sudo chmod 500 myteam 
   87  ls
   88  pwd
   89  ls
   90  cd ..
   91  ls
   92  cd ubuntu
   93  ls
   94  cd ..
   95  ls
   96  cd ubuntu 
   97  whoami
   98  cd myteam
   99  pwd
  100  cd .. 
  101  su - sara
  102  sudo su - sara
  103  whoami
  104  pwd
  105  ls .. 
  106  ls 
  107  cd myteam
  108  cd ..
  109  cd .. 
  110  cd myteam
  111  touch oldpasswd 
  112  sudo touch oldpasswd
  113  ls
  114  ls ..
  115  cd ..
  116  ls
  117  cd my team
  118  cd myteam
  119  cd oldpasswd
  120  ls
  121  sudo ls
  122  cd ..
  123  cd ubuntu
  124  pwd
  125  ls 
  126  cd oldpasswd
  127  cd myteam
  128  cd oldpasswd
  129  ls
  130  ls ..
  131  pwd
  132  ls
  133  cd ..
  134  pwd
  135  sudo chmod 631 oldpasswd
  136  cd .. 
  137  pwd
  138  ls
  139  cd myteam
  140  ls
  141  sudo ls
  142  sudo chmod 631 oldpasswd
  143  ls
  144  cd ..
  145  cd ubuntu
  146  ls
  147  cd myteam
  148  ls
  149  cd oldpasswd
  150  sudo cd oldpasswd
  151  cd .. 
  152  pwd
  153  su - sara
  154  ls
  155  cd myteam
  156  ls
  157  pwd
  158  cd..
  159  cd ..
  160  pwd
  161  ecit
  162  exit
  163  history
  164  ls
  165  pw
  166  pwd
  167  cd ..
  168  ls
  169  cd ubuntu
  170  ls -l
  171  pwd
  172  chmod 662 oldpasswd
  173  cd ..
  174  chmod 662 oldpasswd
  175  sudo chmod 662 oldpasswd
  176  cd myteam
  177  chmod 662 oldpasswd
  178  sudo chmod 662 oldpasswd
  179  ls -l
  180  sudo ls -l
  181  cd .. 
  182  pwd
  183  cd ubuntu 
  184  ls
  185  ls -l 
  186  cd mytem
  187  cd myteam
  188  ls -l 
  189  ls -l oldpasswd
  190  sudo ls -l oldpasswd
  191  cd ..
  192  ls -l 
  193  ls -l oldpasswd
  194  grep| oldpasswd
  195  |grep oldpasswd
  196  pwd
  197  cd myteam
  198  ls -l
  199  ls 
  200  ls .. 
  201  sudo ls
  202  sudo ls -l
  203  sudo chmod 662 oldpasswd
  204  sudo ls -l 
  205  sudo ls -l oldpasswd
  206  sudo chmod u=rw,g=wx,o=x oldpasswd
  207  ls -l oldpasswd
  208  ls
  209  sudo ls
  210  cd oldpasswd
  211  cd .. 
  212  cd ubuntu
  213  ls
  214  sudo ls 
  215  pwd
  216  cd .. 
  217  cd myteam
  218  sudo ls -l oldpasswd
  219  cd ..
  220  pwd
  221  ls
  222  ls ..
  223  pwd
  224  cd ubuntu 
  225  umask 146
  226  sudo ls -l oldpasswd
  227  cd ..
  228  cd myteam
  229  umask 146 
  230  sudo ls -l oldpasswd
  231  touch test 
  232  sudo touch test 
  233  sudo ls -l test
  234  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  235  sudo apt install acl 
  236  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  237  sudo setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  238  sudo ls -l test
  239  sudo touch test2
  240  sudo ls -l test2
  241  umask 146 && touch test3 
  242  sudo umask 146 && touch test3 
  243  umask 146
  244  sudo ls -l test3
  245  sudo ls -l test2
  246  history
  247  pwd
  248  ls
  249  cd ..
  250  ls
  251  cd myteam
  252  ls -l oldpasswd
  253  Get-ChildItem -Path $HOME -Recurse | Where-Object { $_.LastWriteTime -gt (Get-Date).AddDays(-2) }
  254  cd ..
  255  cd ubuntu
  256  pwd
  257  find /etc -user root
  258  find /home -type d
  259  find . -type f
  260  find /home -type f
  261  sudo find /home -type d
  262  sudo rm -r /home/ubuntu/myteam
  263  sudo find /home -type d
  264  find . -type f |grep "profile"
  265  find . -type f |grep ".profile"
  266  sudo find / -type f -name ".profile"
  267  file /etc/passwd
  268  pwd
  269  file /dev/pts/0
  270  file /etc
  271  file /dev/sda
  272  ls -i /etc
  273  ls -i /
  274  ls -i /etc/hosts
  275  cp /etc/passwd /home/ubuntu
  276  diff /etc/passwd /home/ubuntu/passwd
  277  cmpf /etc/passwd /home/ubuntu/passwd
  278  cmp /etc/passwd /home/ubuntu/passwd
  279  pwd
  280  ls
  281  find / -type f
  282  find . -type f
  283  find . -type d
  284  clear
  285  history
  286  sudo find /home -type d
  287  find /home/myteam -type f
  288  sudo find /home/myteam -type f
  289  whoami
  290  cmp /etc/passwd /home/ubuntu/passwd
  291  nano /home/ubuntu/passwd
  292  diff /etc/passwd /home/ubuntu/passwd
  293  ls ..
  294  tail -n 8 cat /etc/passwd
  295  tail -n 8 cat /home/ubuntu/passwd
  296  sudo ln -s /etc/passwd /boot/passwd
  297  ls -l boot/passwd
  298  ls -l /boot/passwd
  299  cat /boot/passwd
  300  clear
  301  history
  302  ps
  303  git init
  304  git add README.md
  305  git commit -m "first commit"
  306  git add .
  307  git commit -m "Initial commit of my code"
  308  git remote add origin https://github.com/saramostafa01/lab3_linux.git
  309  git commit -m "Initial commit of my Multipass code"
  310  git push -u origin master main
  311  git push -u origin main master
  312  git config --global user.name "saramostafa01"
  313  clear
  314  history
  315  git branch
  316  git checkout -b main
  317  git add .
  318  git commit -m "Initial commit"
  319  git push -u origin main
  320  git checkout -b master
  321* 
  322  touch README.md
  323  git add README.md
  324  git commit -m "Add README.md

git push origin main
clear


git add README.md
























clear
  325  clear
  326  git push origin main
  327  git add README.md
  328  git commit -m "Add README.md"
  329  git push origin main
  330  history
  331  history >> README.md
    1  history
    2  clear
    3  echo $fullname
    4  exit
    5  echo $fullname
    6  export fullname="ali mustafa"
    7  echo $fullname
    8  exit
    9  echo $fullname
   10  exit
   11  fullname="sara mostafa"
   12  echo $fullname
   13  bash
   14  echo $fullname
   15  export fullname
   16  bash
   17  echo $fullname
   18  bash
   19  man bash
   20  ls
   21  pwd
   22  clear
   23  pwd
   24  sudo useradd sara -c "sara mostafa" -m
   25  sudo passwd sara
   26  sudo useradd baduser -c "Bad User" -m 
   27  sudo passwd baduser
   28  ls -l
   29  ls ..
   30  pwd
   31  cat /etc/passwd
   32  tail -n 3 /etc/passwd
   33  groupadd -g 30000 pgroup
   34  sudo groupadd -g 30000 pgroup
   35  ls ..
   36  getent group pgroup 
   37  sudo groupadd -g badgroup 
   38  sudo groupadd badgroup 
   39  cat /etc/groups
   40  cat /etc/group
   41  sudo usermod -a -G sara pgroup
   42  sudo usermod -a -G pgroup sara
   43  getent group pgroup
   44  sudo passwd sara
   45  ls ..
   46  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara1
   47  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara
   48  sudo chage --expiredate $(date -d +30days +%Y-%m-%d) sara
   49  sudo passwd -1 baduser 
   50  sudo passwd -l baduser 
   51  sudo deluser baduser
   52  ls ..
   53  sudo deluser --remove-home baduser
   54  ls .. 
   55  cat /etc/passwd |grep baduser
   56  sudo rm -rf /home/baduser
   57  ls ..
   58  pwd
   59  sudo groupdel badgroup 
   60  tail -n 5 /etc/group
   61  cd 
   62  pwd
   63  cd .. 
   64  pwd
   65  touch myteam 
   66  cd ubuntu
   67  pwd
   68  sudo passwd ubuntu 
   69  cd ..
   70  mkdir myteam
   71  mkdir ~/myteam
   72  ls 
   73  pwd
   74  cd /myteam
   75  cat |grep myteam
   76  cd .. 
   77  ls
   78  cd home
   79  ls
   80  sudo mkdir myteam
   81  ls
   82  chmod ugo+r myteam
   83  sudo chmod ugo+r myteam
   84  sudo chmod ugo-r myteam
   85  cd ubuntu
   86  sudo chmod 500 myteam 
   87  ls
   88  pwd
   89  ls
   90  cd ..
   91  ls
   92  cd ubuntu
   93  ls
   94  cd ..
   95  ls
   96  cd ubuntu 
   97  whoami
   98  cd myteam
   99  pwd
  100  cd .. 
  101  su - sara
  102  sudo su - sara
  103  whoami
  104  pwd
  105  ls .. 
  106  ls 
  107  cd myteam
  108  cd ..
  109  cd .. 
  110  cd myteam
  111  touch oldpasswd 
  112  sudo touch oldpasswd
  113  ls
  114  ls ..
  115  cd ..
  116  ls
  117  cd my team
  118  cd myteam
  119  cd oldpasswd
  120  ls
  121  sudo ls
  122  cd ..
  123  cd ubuntu
  124  pwd
  125  ls 
  126  cd oldpasswd
  127  cd myteam
  128  cd oldpasswd
  129  ls
  130  ls ..
  131  pwd
  132  ls
  133  cd ..
  134  pwd
  135  sudo chmod 631 oldpasswd
  136  cd .. 
  137  pwd
  138  ls
  139  cd myteam
  140  ls
  141  sudo ls
  142  sudo chmod 631 oldpasswd
  143  ls
  144  cd ..
  145  cd ubuntu
  146  ls
  147  cd myteam
  148  ls
  149  cd oldpasswd
  150  sudo cd oldpasswd
  151  cd .. 
  152  pwd
  153  su - sara
  154  ls
  155  cd myteam
  156  ls
  157  pwd
  158  cd..
  159  cd ..
  160  pwd
  161  ecit
  162  exit
  163  history
  164  ls
  165  pw
  166  pwd
  167  cd ..
  168  ls
  169  cd ubuntu
  170  ls -l
  171  pwd
  172  chmod 662 oldpasswd
  173  cd ..
  174  chmod 662 oldpasswd
  175  sudo chmod 662 oldpasswd
  176  cd myteam
  177  chmod 662 oldpasswd
  178  sudo chmod 662 oldpasswd
  179  ls -l
  180  sudo ls -l
  181  cd .. 
  182  pwd
  183  cd ubuntu 
  184  ls
  185  ls -l 
  186  cd mytem
  187  cd myteam
  188  ls -l 
  189  ls -l oldpasswd
  190  sudo ls -l oldpasswd
  191  cd ..
  192  ls -l 
  193  ls -l oldpasswd
  194  grep| oldpasswd
  195  |grep oldpasswd
  196  pwd
  197  cd myteam
  198  ls -l
  199  ls 
  200  ls .. 
  201  sudo ls
  202  sudo ls -l
  203  sudo chmod 662 oldpasswd
  204  sudo ls -l 
  205  sudo ls -l oldpasswd
  206  sudo chmod u=rw,g=wx,o=x oldpasswd
  207  ls -l oldpasswd
  208  ls
  209  sudo ls
  210  cd oldpasswd
  211  cd .. 
  212  cd ubuntu
  213  ls
  214  sudo ls 
  215  pwd
  216  cd .. 
  217  cd myteam
  218  sudo ls -l oldpasswd
  219  cd ..
  220  pwd
  221  ls
  222  ls ..
  223  pwd
  224  cd ubuntu 
  225  umask 146
  226  sudo ls -l oldpasswd
  227  cd ..
  228  cd myteam
  229  umask 146 
  230  sudo ls -l oldpasswd
  231  touch test 
  232  sudo touch test 
  233  sudo ls -l test
  234  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  235  sudo apt install acl 
  236  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  237  sudo setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  238  sudo ls -l test
  239  sudo touch test2
  240  sudo ls -l test2
  241  umask 146 && touch test3 
  242  sudo umask 146 && touch test3 
  243  umask 146
  244  sudo ls -l test3
  245  sudo ls -l test2
  246  history
  247  pwd
  248  ls
  249  cd ..
  250  ls
  251  cd myteam
  252  ls -l oldpasswd
  253  Get-ChildItem -Path $HOME -Recurse | Where-Object { $_.LastWriteTime -gt (Get-Date).AddDays(-2) }
  254  cd ..
  255  cd ubuntu
  256  pwd
  257  find /etc -user root
  258  find /home -type d
  259  find . -type f
  260  find /home -type f
  261  sudo find /home -type d
  262  sudo rm -r /home/ubuntu/myteam
  263  sudo find /home -type d
  264  find . -type f |grep "profile"
  265  find . -type f |grep ".profile"
  266  sudo find / -type f -name ".profile"
  267  file /etc/passwd
  268  pwd
  269  file /dev/pts/0
  270  file /etc
  271  file /dev/sda
  272  ls -i /etc
  273  ls -i /
  274  ls -i /etc/hosts
  275  cp /etc/passwd /home/ubuntu
  276  diff /etc/passwd /home/ubuntu/passwd
  277  cmpf /etc/passwd /home/ubuntu/passwd
  278  cmp /etc/passwd /home/ubuntu/passwd
  279  pwd
  280  ls
  281  find / -type f
  282  find . -type f
  283  find . -type d
  284  clear
  285  history
  286  sudo find /home -type d
  287  find /home/myteam -type f
  288  sudo find /home/myteam -type f
  289  whoami
  290  cmp /etc/passwd /home/ubuntu/passwd
  291  nano /home/ubuntu/passwd
  292  diff /etc/passwd /home/ubuntu/passwd
  293  ls ..
  294  tail -n 8 cat /etc/passwd
  295  tail -n 8 cat /home/ubuntu/passwd
  296  sudo ln -s /etc/passwd /boot/passwd
  297  ls -l boot/passwd
  298  ls -l /boot/passwd
  299  cat /boot/passwd
  300  clear
  301  history
  302  ps
  303  git init
  304  git add README.md
  305  git commit -m "first commit"
  306  git add .
  307  git commit -m "Initial commit of my code"
  308  git remote add origin https://github.com/saramostafa01/lab3_linux.git
  309  git commit -m "Initial commit of my Multipass code"
  310  git push -u origin master main
  311  git push -u origin main master
  312  git config --global user.name "saramostafa01"
  313  clear
  314  history
  315  git branch
  316  git checkout -b main
  317  git add .
  318  git commit -m "Initial commit"
  319  git push -u origin main
  320  git checkout -b master
  321* 
  322  touch README.md
  323  git add README.md
  324  git commit -m "Add README.md

git push origin main
clear


git add README.md
























clear
  325  clear
  326  git push origin main
  327  git add README.md
  328  git commit -m "Add README.md"
  329  git push origin main
  330  history
  331  history >> README.md
  332  git add README.md
  333  git commit -m "Add README.md"
  334  git push origin main
  335  touch README.md
  336  history 
  337  history >> README.md
# lab4_linux
# lab3_linux
    1  history
    2  clear
    3  echo $fullname
    4  exit
    5  echo $fullname
    6  export fullname="ali mustafa"
    7  echo $fullname
    8  exit
    9  echo $fullname
   10  exit
   11  fullname="sara mostafa"
   12  echo $fullname
   13  bash
   14  echo $fullname
   15  export fullname
   16  bash
   17  echo $fullname
   18  bash
   19  man bash
   20  ls
   21  pwd
   22  clear
   23  pwd
   24  sudo useradd sara -c "sara mostafa" -m
   25  sudo passwd sara
   26  sudo useradd baduser -c "Bad User" -m 
   27  sudo passwd baduser
   28  ls -l
   29  ls ..
   30  pwd
   31  cat /etc/passwd
   32  tail -n 3 /etc/passwd
   33  groupadd -g 30000 pgroup
   34  sudo groupadd -g 30000 pgroup
   35  ls ..
   36  getent group pgroup 
   37  sudo groupadd -g badgroup 
   38  sudo groupadd badgroup 
   39  cat /etc/groups
   40  cat /etc/group
   41  sudo usermod -a -G sara pgroup
   42  sudo usermod -a -G pgroup sara
   43  getent group pgroup
   44  sudo passwd sara
   45  ls ..
   46  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara1
   47  sudo chage --expiredate $(date -d +90days +%Y-%m-%d) sara
   48  sudo chage --expiredate $(date -d +30days +%Y-%m-%d) sara
   49  sudo passwd -1 baduser 
   50  sudo passwd -l baduser 
   51  sudo deluser baduser
   52  ls ..
   53  sudo deluser --remove-home baduser
   54  ls .. 
   55  cat /etc/passwd |grep baduser
   56  sudo rm -rf /home/baduser
   57  ls ..
   58  pwd
   59  sudo groupdel badgroup 
   60  tail -n 5 /etc/group
   61  cd 
   62  pwd
   63  cd .. 
   64  pwd
   65  touch myteam 
   66  cd ubuntu
   67  pwd
   68  sudo passwd ubuntu 
   69  cd ..
   70  mkdir myteam
   71  mkdir ~/myteam
   72  ls 
   73  pwd
   74  cd /myteam
   75  cat |grep myteam
   76  cd .. 
   77  ls
   78  cd home
   79  ls
   80  sudo mkdir myteam
   81  ls
   82  chmod ugo+r myteam
   83  sudo chmod ugo+r myteam
   84  sudo chmod ugo-r myteam
   85  cd ubuntu
   86  sudo chmod 500 myteam 
   87  ls
   88  pwd
   89  ls
   90  cd ..
   91  ls
   92  cd ubuntu
   93  ls
   94  cd ..
   95  ls
   96  cd ubuntu 
   97  whoami
   98  cd myteam
   99  pwd
  100  cd .. 
  101  su - sara
  102  sudo su - sara
  103  whoami
  104  pwd
  105  ls .. 
  106  ls 
  107  cd myteam
  108  cd ..
  109  cd .. 
  110  cd myteam
  111  touch oldpasswd 
  112  sudo touch oldpasswd
  113  ls
  114  ls ..
  115  cd ..
  116  ls
  117  cd my team
  118  cd myteam
  119  cd oldpasswd
  120  ls
  121  sudo ls
  122  cd ..
  123  cd ubuntu
  124  pwd
  125  ls 
  126  cd oldpasswd
  127  cd myteam
  128  cd oldpasswd
  129  ls
  130  ls ..
  131  pwd
  132  ls
  133  cd ..
  134  pwd
  135  sudo chmod 631 oldpasswd
  136  cd .. 
  137  pwd
  138  ls
  139  cd myteam
  140  ls
  141  sudo ls
  142  sudo chmod 631 oldpasswd
  143  ls
  144  cd ..
  145  cd ubuntu
  146  ls
  147  cd myteam
  148  ls
  149  cd oldpasswd
  150  sudo cd oldpasswd
  151  cd .. 
  152  pwd
  153  su - sara
  154  ls
  155  cd myteam
  156  ls
  157  pwd
  158  cd..
  159  cd ..
  160  pwd
  161  ecit
  162  exit
  163  history
  164  ls
  165  pw
  166  pwd
  167  cd ..
  168  ls
  169  cd ubuntu
  170  ls -l
  171  pwd
  172  chmod 662 oldpasswd
  173  cd ..
  174  chmod 662 oldpasswd
  175  sudo chmod 662 oldpasswd
  176  cd myteam
  177  chmod 662 oldpasswd
  178  sudo chmod 662 oldpasswd
  179  ls -l
  180  sudo ls -l
  181  cd .. 
  182  pwd
  183  cd ubuntu 
  184  ls
  185  ls -l 
  186  cd mytem
  187  cd myteam
  188  ls -l 
  189  ls -l oldpasswd
  190  sudo ls -l oldpasswd
  191  cd ..
  192  ls -l 
  193  ls -l oldpasswd
  194  grep| oldpasswd
  195  |grep oldpasswd
  196  pwd
  197  cd myteam
  198  ls -l
  199  ls 
  200  ls .. 
  201  sudo ls
  202  sudo ls -l
  203  sudo chmod 662 oldpasswd
  204  sudo ls -l 
  205  sudo ls -l oldpasswd
  206  sudo chmod u=rw,g=wx,o=x oldpasswd
  207  ls -l oldpasswd
  208  ls
  209  sudo ls
  210  cd oldpasswd
  211  cd .. 
  212  cd ubuntu
  213  ls
  214  sudo ls 
  215  pwd
  216  cd .. 
  217  cd myteam
  218  sudo ls -l oldpasswd
  219  cd ..
  220  pwd
  221  ls
  222  ls ..
  223  pwd
  224  cd ubuntu 
  225  umask 146
  226  sudo ls -l oldpasswd
  227  cd ..
  228  cd myteam
  229  umask 146 
  230  sudo ls -l oldpasswd
  231  touch test 
  232  sudo touch test 
  233  sudo ls -l test
  234  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  235  sudo apt install acl 
  236  setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  237  sudo setfacl -m d:u::rw,d:g::wx,d:o::x /home/myteam
  238  sudo ls -l test
  239  sudo touch test2
  240  sudo ls -l test2
  241  umask 146 && touch test3 
  242  sudo umask 146 && touch test3 
  243  umask 146
  244  sudo ls -l test3
  245  sudo ls -l test2
  246  history
  247  pwd
  248  ls
  249  cd ..
  250  ls
  251  cd myteam
  252  ls -l oldpasswd
  253  Get-ChildItem -Path $HOME -Recurse | Where-Object { $_.LastWriteTime -gt (Get-Date).AddDays(-2) }
  254  cd ..
  255  cd ubuntu
  256  pwd
  257  find /etc -user root
  258  find /home -type d
  259  find . -type f
  260  find /home -type f
  261  sudo find /home -type d
  262  sudo rm -r /home/ubuntu/myteam
  263  sudo find /home -type d
  264  find . -type f |grep "profile"
  265  find . -type f |grep ".profile"
  266  sudo find / -type f -name ".profile"
  267  file /etc/passwd
  268  pwd
  269  file /dev/pts/0
  270  file /etc
  271  file /dev/sda
  272  ls -i /etc
  273  ls -i /
  274  ls -i /etc/hosts
  275  cp /etc/passwd /home/ubuntu
  276  diff /etc/passwd /home/ubuntu/passwd
  277  cmpf /etc/passwd /home/ubuntu/passwd
  278  cmp /etc/passwd /home/ubuntu/passwd
  279  pwd
  280  ls
  281  find / -type f
  282  find . -type f
  283  find . -type d
  284  clear
  285  history
  286  sudo find /home -type d
  287  find /home/myteam -type f
  288  sudo find /home/myteam -type f
  289  whoami
  290  cmp /etc/passwd /home/ubuntu/passwd
  291  nano /home/ubuntu/passwd
  292  diff /etc/passwd /home/ubuntu/passwd
  293  ls ..
  294  tail -n 8 cat /etc/passwd
  295  tail -n 8 cat /home/ubuntu/passwd
  296  sudo ln -s /etc/passwd /boot/passwd
  297  ls -l boot/passwd
  298  ls -l /boot/passwd
  299  cat /boot/passwd
  300  clear
  301  history
  302  ps
  303  git init
  304  git add README.md
  305  git commit -m "first commit"
  306  git add .
  307  git commit -m "Initial commit of my code"
  308  git remote add origin https://github.com/saramostafa01/lab3_linux.git
  309  git commit -m "Initial commit of my Multipass code"
  310  git push -u origin master main
  311  git push -u origin main master
  312  git config --global user.name "saramostafa01"
  313  clear
  314  history
  315  git branch
  316  git checkout -b main
  317  git add .
  318  git commit -m "Initial commit"
  319  git push -u origin main
  320  git checkout -b master
  321* 
  322  touch README.md
  323  git add README.md
  324  git commit -m "Add README.md

git push origin main
clear


git add README.md
























clear
  325  clear
  326  git push origin main
  327  git add README.md
  328  git commit -m "Add README.md"
  329  git push origin main
  330  history
  331  history >> README.md
  332  git add README.md
  333  git commit -m "Add README.md"
  334  git push origin main
  335  touch README.md
  336  history 
  337  history >> README.md
  338  git commit -m "Add README.md"
  339  git push -m "Add README.md"
  340  echo "# lab4_linux" >> README.md
  341  echo "# lab3_linux" >> README.md
  342  git add README.md
  343  history >> README.md
