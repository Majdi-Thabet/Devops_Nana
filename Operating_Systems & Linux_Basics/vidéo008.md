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

Result  : Filtering the history entries that start with 'sudo' word command. 

``` history | grep "sudo chmod" ```

Result  : Filtering the history entries that start with 'sudo chmod' string.

we can pass the output of a program in another program too:

``` history | grep sudo | less``` 
so in our exp, less will contain the filter of sudo word from history commands.

### Redirects in Linux (min 14:11)

we can redirect the result of command execution into a file for exp.

We saw how to filter the history entries that start with 'sudo' word command. we want to save the outpu of command ```history | grep sudo ``` into a file. This is done by redirecting the result of this prog into a file by using : **>**

``` history | grep sudo > sudo-commands.txt```

to veify : 

```cat sudo-commands.txt```

we use **>>** : to append text to end of file.








