# minishell
42/Codam minishell, a simple shell based on bash
## Description
A collaborative group project that has us writing our own simple little shell in C.

The shell takes single-line inputs and replicates bash behaviour.

It supports:
* redirections - ```<```, ```>```, and ```>>```.
* pipes - ```|```
* separating semicolons - ```;```
* single and double quotes - ```'``` ```"```
* escape character - ```\```
* environment variables - ```$```
* ```ctrl-C```, ```ctrl-D```, and ```ctrl-\```

Implemented builtins:
* ```echo``` with option ’-n’
* ```cd``` with relative or absolute path, and '-'
* ```pwd``` without any options
* ```export``` without any options
* ```unset``` without any options
* ```env``` without any options and any arguments
* ```exit``` without any options

## Commands
```
# Build
make

# Run
./minishell
```
## Demo
<img src="/minishell.png" width="650" title="minishell">

## Resources
[Bash repo](https://github.com/bminor/bash)

[man pages for bash commands](https://man7.org/linux/man-pages/dir_all_by_section.html)

[A guide to writing your own shell from *Introduction to Systems Programming*](https://www.cs.purdue.edu/homes/grr/SystemsProgrammingBook/Book/Chapter5-WritingYourOwnShell.pdf)

[A detailed breakdown of how the shell interprets commands](https://pubs.opengroup.org/onlinepubs/009604499/utilities/xcu_chap02.html)

[Pipes, forks, and dups - data flows explained](http://www.rozmichelle.com/pipes-forks-dups)

[An explanation of shell operators](https://unix.stackexchange.com/questions/159513/what-are-the-shells-control-and-redirection-operators)

[Environment variable naming conventions](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap08.html)

[Process statuses](https://www.gnu.org/software/libc/manual/html_node/Process-Completion-Status.html)

[Special exit codes (version-dependant)](https://tldp.org/LDP/abs/html/exitcodes.html#EXITCODESREF)
