## Title pipes and redirects

Every command in Linux has an input and output, and the output from one command can become the input of onother command.

Exp : We have a file named syslog which contains a lot of informations.

We would like to print the content of syslog file but not in the CLI, so we decided to redirect the content of file to a program inttled "less".

 ``` cat /var/log/syslog | less ```

