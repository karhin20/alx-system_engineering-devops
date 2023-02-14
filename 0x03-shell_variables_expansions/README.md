Shell, init files, variables and expansions

**Note that all scripts in this files are preceded by   #!/bin/bash

0. alias scripts named ls with value rm *
   alias = ls="rm *"

1. Prints Hello User
echo "hello $USER"

2. Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
 export PATH=$PATH:/action

4. script that lists environment variables
 printenv

