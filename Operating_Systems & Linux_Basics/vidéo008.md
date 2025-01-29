## Title pipes and redirects

Every command in Linux has an input and output. The output from one command can become the input of onother command.

Exp : We have a file named syslog which contains a lot of informations.

We would like to print the content of syslog file but not in the CLI, so we decided to redirect the content of file to a onother program inttled "less" to read it in interactive (page by page) mode.

 ``` cat /var/log/syslog | less ```

to quit the pages tape : **q**

to go back to a previous page :**qb**

### Pipe and Grep (min 7:40)

we can filter the outpu of cammand to search for a particular pattern for exp:

```history | grep sudo```

Result  : Having only all commands that start with 'sudo' word. 

``` history | grep "sudo chmod" ```

Result  : Having only all commands that start with 'sudo chmod' string.
