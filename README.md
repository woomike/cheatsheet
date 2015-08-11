## Setup and Info cheatsheet! ##

1) Touch a file 'i' somewhere in your $PATH (/usr/local/bin/i)
1a) mkdir 'cheatsheet' in your Home
2) Inside write:

#!/bin/bash

if [ $1 ]; then
  cat ~/cheatsheet/$1*
  else
    ls ~/cheatsheet/
  fi

3) In cheatsheet touch files 'git', 'vim', 'docker', etc.
4) Write down any notes or commands you want to remember
5) Type 'i git' to see your file (works with grep and less as well)
