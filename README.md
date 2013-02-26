```
ENV(1)                  User Commands                   ENV(1)

NAME
       env - program in a modified environment

SYNOPSIS
       env [OPTION]... [-] [NAME=VALUE]... [COMMAND [ARG]...]

DESCRIPTION
       Set each NAME to VALUE in the environment and run COMMAND.

       -i, --ignore-environment
              start with an empty environment

       -0, --null
              end each output line with 0 byte rather than newline

       -u, --unset=NAME
              remove variable from the environment

       --help display this help and exit

       --version
              output version information and exit

       A mere - implies -i.  If no COMMAND, print the resulting environment.

AUTHOR
       Written by Richard Mlynarik and David MacKenzie.

REPORTING BUGS
       Report env bugs to bug-coreutils@gnu.org
       GNU coreutils home page: <http://www.gnu.org/software/coreutils/>
       General help using GNU software: <http://www.gnu.org/gethelp/>
       Report env translation bugs to <http://translationproject.org/team/>

COPYRIGHT
       Copyright © 2011 Free Software Foundation, Inc.  License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>.
       This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted by law.

SEE ALSO
       The full documentation for env is maintained as a Texinfo manual.  If the info and env programs are properly installed at your site, the command

              info coreutils 'env invocation'

       should give you access to the complete manual.
```
 Manual page env(1) line 1/52 (END) (press h for help or q to quit)
