# Bash

## Built-in Commands

Built-in commands are contained within the shell itself.

### Shell Control

|Command|Description|
|--|--|
|`bind`|Set or display readline key bindings and function bindings|
|`exit`|Exit the shell|
|`history`|Display shell history|
|`logout`|Exit a login shell|

### Directories & Files

|Command|Description|
|--|--|
|`cd`|Change the working directory|
|`pwd`|Print working directory|
|`umask`|Change the default permissions given to files when they are created|

### Commands Execution

|Command|Description|
|--|--|
|`.`<br />`source`|Execute commands from a file|
|`alias`/`unalias`|Set/unset an alias to a command|
|`builtin`|Run a built-in command|
|`command`|Run a command ignoring aliases and function names|
|`help`|Display help for a built-in command|
|`exec`|Destroy current shell and run a command|
|`time`|Measure the running time of a program|
|`trap`|Run a command when the shell receives a signal|
|`type`|Describe a command|

### Processes & Jobs

|Command|Description|
|--|--|
|`bg`/`fg`|Send a job to background/foreground|
|`coproc`|Create a coprocess|
|`disown`|Remove jobs from the shell's table of active jobs|
|`jobs`|Jobs and their status|
|`kill`|Terminate a process|
|`suspend`|Suspend current job|
|`times`|Display accumulated user and system times for the shell and for all of its child processes|
|`wait`|Wait for a process to complete|

### Scripting

|Command|Description|
|--|--|
|`:`|Return successful exit status|
|`declare`|Declare variables and give them attributes|
|`echo`|Output arguments|
|`eval`|Concatenate the arguments with spaces, then execute the string|
|`export`|Set an environment variable|
|`let`|Evaluate an expression on a variable|
|`printf`|Format and print|
|`read`|Read a line from standard input and assign to a variable|
|`readarray`|Read lines from standard input and assign to an array|
|`readonly`|Set variables and functions as read only|
|`set`/`unset`|Set/unset variables and functions|
|`shift`|Shift left command line arguments|
|`true`/`false`|Return successful/unsuccessful exit status|

## External Commands

Programs that are not built into the shell, typically located in directories like `/bin` or `/usr/bin`.

|Command|Description|
|--|--|
|`clear`|Clear the terminal screen|

### Directories & Files

|Command|Description|
|--|--|
|`cat`|Concatenate files and print on the standard output|
|`chgrp`|Change file group ownership|
|`chmod`|Change file access permissions|
|`chown`|Change file owner and group|
|`cmp`|Compare two files by character|
|`cp`|Copy a file/directory|
|`diff`|Compare two files by line|
|`du`|Summarize disk usage of the set of files|
|`file`|Determine file type|
|`find`|Search for files|
|`ln`|Create a link to a file|
|`locate`|Search database of filenames|
|`ls`|List information about the files|
|`mkdir`|Create a directory|
|`more`/`less`|Display output one page at a time (less is more functional)|
|`mv`|Move or rename a file/directory|
|`rm`|Remove a file|
|`rmdir`|Remove an empty directory|
|`tar`|Archive files, uncompressed|
|`touch`|Change timestamps of a file or create it|
|`whereis`|Search the user's $path for binaries, man pages and source files|
|`which`|Search the user's $path for a program file|
|`zip`/`unzip`<br />`gzip`/`gunzip`<br />`bzip2`/`bunzip2`|Compress/decompress files|

### Help

|Command|Description|
|--|--|
|`apropos`|Find in documentation
|`man`|Help manual
|`info`|Find in documentation|
|`whatis`|Find one-line description in documentation|

#### Manual Controls

|Command|Description|
|--|--|
|`F`/`PAGEUP`|Forward|
|`B`/`PAGEDOWN`|Back|
|`Q`|Quit|
|`/`_str_|Search for _string_|
|`/`|Search next|
|`?`|Search previous|

### Scripting

|Command|Description|
|--|--|
|`expr`|Evaluate an expression and write to standard output|
|`seq`|Print a sequence of numbers|
|`sleep`|Pause for a specified time|

### Text Manipulation

|Command|Description|
|--|--|
|`fgrep`|Search lines that match a string|
|`grep`/`egrep`|Search lines that match a regexp/extended regexp|
|`head`/`tail`|Print first/last lines|
|`pr`|Prepare files for printing|
|`rev`|Reverse lines|
|`sed`|Stream editor for filtering and transforming text|
|`sort`|Sort lines|
|`tsort`|Sort string separated by blanks|
|`uniq`|Report or filter out repeated lines|
|`wc`|Print byte, word, and line counts|
|`yes`|Print a string forever until killed, default "y"|

### System

|Command|Description|
|--|--|
|`apt-get`|Search for and install software packages|
|`cal`|Print a calendar|
|`crontab`|Schedule a task|
|`date`|Print or set date-time|
|`df`|Display used and available disk space|
|`env`|Environment variables|
|`free`|Display memory usage|
|`halt`|Stop the system|
|`hostname`|Print or set hostname|
|`lpr`|Send a print job|
|`lprm`|Remove jobs from the print queue|
|`mount`|Mount a file system|
|`poweroff`|System power down|
|`reboot`|Reboot the system|
|`service`|Control services|
|`shutdown`|Shutdown or reboot the system|
|`uname`|System information|

### Commands Execution

|Command|Description|
|--|--|
|`timeout`|Run a command with a time limit|
|`watch`|Run a command periodically|
|`xargs`|Run a command over each set of lines|

### Processes & Jobs

|Command|Description|
|--|--|
|`killall`|Terminate a group of processes by name|
|`nice`|Run a job with specified priority|
|`nohup`|Run a job immune to hangups|
|`ps`|Process status|
|`renice`|Change priority of running process|
|`top`|List processes sorted by CPU usage|

### Users & Groups

|Command|Description|
|--|--|
|`groupadd`|Add a group|
|`groupdel`|Delete a group|
|`groupmod`|Modify a group|
|`groups`|Current user groups|
|`id`|User and group information|
|`passwd`|Set user password|
|`su`|Substitute user identity|
|`sudo`|Execute a command as another user|
|`useradd`|Create a new user|
|`userdel`|Delete a user|
|`usermod`|Modify a user|
|`w`|Logged-in users and their processes|
|`wall`|Broadcasts a message to all users|
|`who`|Logged-in users|
|`whoami`|Current user name|
|`write`|Send a message to another user|

### Network

|Command|Description|
|--|--|
|`curl`|Transfer data from/to a server|
|`ftp`|Connect using File Transfer Protocol|
|`ifconfig`|Configure a network interface|
|`netstat`|Networking connections information|
|`ping`|Test a network connection|
|`scp`|Remote file copy using Secure Shell|
|`ssh`|Connect using Secure Shell client|

## Shortcuts

|Shortcut|Description|
|--|--|
|`Up`/`Down`|Previous/next command|
|`Tab`|Auto-complete|
|`Ctrl + C`<br />`Ctrl + \`|Kill process|
|`Ctrl + D`|End the input; Exit|
|`Ctrl + L`|Clear screen|
|`Ctrl + S`/`Q`|Freeze/unfreeze terminal|
|`Ctrl + Z`|Suspend process|

## Operators

|Operator|Description|
|--|--|
|`#`|Comment, anything in the line after # will be ignored|
|`\`_char_|Escape character|
|`'`_str_`'`<br />`"`_str_`"`|Preserves the literal value of each character|
|`$`_var_|Get the value of a variable|
|`((`_expr_`))`|Evaluate an expression|
|`$((`_expr_`))`|Evaluate an expression and substitute the expression with the result|
|`[`_expr_`]`|Condition test|
|`[[`_expr_`]]`|Extended condition test|

### Control Operators

|Operator|Description|
|--|--|
|_cmd_ `&`|Run a job in the background|
|_cmd_ `;` _cmd_|Separate commands, commands will be executed in sequence|
|_cmd_ `&&` _cmd_|Run command if previous was successful|
|_cmd_ `\|\|` _cmd_|Run command if previous was unsuccessful|
|`(`_commands_`)`|Group commands, commands will be executed in a subshell|
|`{`_commands_`;}`|Group commands, commands will be executed in a current shell|

### Arithmetic Operators

|Operator|Description|
|--|--|
|_var_`++`<br />_var_`--`|Post-increment/decrement|
|`++`_var_<br />`--`_var_|Pre-increment/decrement|
|`-`_expr_<br />`+`_expr_|Unary minus/plus|
|`+`|Addition|
|`-`|Subtraction|
|`*`|Multiplication|
|`/`|Division|
|`%`|Remainder (modulo)|
|`**`|Exponentiation|
|`==`/`!=`|Equality, Inequality|
|`<`/`>`|Less/greater than|
|`<=`/`>=`|Less/greater than or equal to|
|`!`|Logical negation|
|`&&`|Logical AND|
|`\|\|`|Logical OR|
|`~`|Bitwise negation|
|`&`|Bitwise AND|
|`\|`|Bitwise OR|
|`^`|Bitwise XOR|
|`<<`/`>>`|Bitwise shift left/right|
|_expr_ `?` _expr_ `:` _expr_|Conditional (ternary) operator|
|_var_`=`_expr_|Assignment|
|_var__op_`=`_expr_|Same as _var_`=`_var_ _op_ _expr_|

### Redirections

|Operator|Description|
|--|--|
|_fd_`<>` _file_|Opens a file for reading and writing and assigns the file descriptor to it|
|_fd_`<&-`|Close input|
|_fd_`>&-`|Close output|
|_fd_`>` _file_<br />_fd_`>&`_fd_|Redirect output (overwrite), default stdout if file descriptor is not specified|
|`$>` _file_|Redirect stdout and stderr (overwrite)|
|_fd_`>\|` _file_<br />_fd_`>\|&`_fd_|Redirect output (overwrite), ignores if shell is configured to refuse overwriting, default stdout|
|_fd_`>>` _file_<br />_fd_`>>&`_fd_|Redirect output (append), default stdout|
|`$>>` _file_|Redirect stdout and stderr (append)|
|_fd_`<` _file_<br />_fd_`<&`_fd_|Redirect input, default stdin|
|_cmd_ `\|` _cmd_|Pipe, redirect output of the command to the input of the other command|
|_cmd_ `\|&` _cmd_|Pipe, redirect output and error of the command to the input of the other command|

File descriptors 0, 1, and 2 are reserved for stdin, stdout, and stderr.  
Child processes inherit open file descriptors.

#### Special Device Files

|Device|Description|
|--|--|
|`/dev/null`|Null device<br />Discards data written to and reports that the write succeeded|
|`/dev/random`|Generates a pseudo-random number|
|`/dev/stderr`|Default file descriptor where a process write error messages|
|`/dev/stdin`|Default file descriptor where data is sent to and read by a process|
|`/dev/stdout`|Default file descriptor where a process write output|
|`/dev/zero`|Provides null characters|

## Statements

```bash
# if conditional statement

# Conditional expression can be evaluated using:
# test expr
# [expr]
# [[expr]]

if test-commands
then
    commands;
[ elif test-commands
then
    commands; ...]
[ else commands; ]
fi
```

```bash
# case conditional statement, * is default
case variable in
    [ pattern [ | pattern ...]) commands;; ...]
    [ *) commands;; ]
esac
```

```bash
# while loop
while test-commands
do
    commands;
done
```

```bash
# until loop
until test-commands
do
    commands
done
```

```bash
# for loop
for variable [ in list ]
do
    commands;
done

for ((expr1; expr2; expr3))
do
    commands;
done
```

`break` Exits the loop.  
`continue` Resume the next iteration of a loop.

```bash
# select construct - used for generation of text menus

# 1. Outputs the specified words, each preceded by a number of the position in the list
# 2. Outputs PS3 prompt string
# 3. Reads a line from the standard input
# 4.1. If the input consists of a number corresponding to one of the words, then sets the value of the variable to that word
# 4.2. If the input is empty, displays the words and prompt again
# 4.3. If the input is any other value, then sets the variable to null
# The line read is saved in the variable REPLY
# 5. The commands are executed after each selection until a break command is executed

[PS3=prompt string]
select variable in [in words ...];
do
    commands;
done
```

```bash
# function definition

# local - Create a local variable.  
# return - Exit the function.

[ function ] name () {
    commands;
}
```

## History Expansions

History expansions introduce words from the history list into the input stream.

### Event Designators

|Designator|Description|
|--|--|
|`!`_n_|Refer to the command line _n_ in command history|
|`!-`_n_|Refer to the command _n_ lines back|
|`!`_str_|Refer to the last command that starts with specified _string_|
|`!?`_str_[`?`]|Refer to the last command that contains the specified _string_, trailing `?` may be omitted if the _string_ is followed immediately by a newline|
|`!!`|Refer to the previous command|
|`!#`|Refer to the entire command line typed so far|
|`^`_str_`^`_str_|Refer to the previous command replacing first _string_ with the second|

### Word Designators

Placed at the end of the event designator.

|Designator|Description|
|--|--|
|`:`_n_|Refer to the _nth_ word, starting from 0|
|`:^`/`^`|Refer to the first word after 0|
|`:$`/`$`|Refer to the last word|
|`:*`/`*`|Refer to all of the words after 0|
|`:`_n1_`-`_n2_|Refer to all of the words from n1 to n2|
|`:`_n_`*`|Refer to all of the words starting from n|
|`:`_n_`-`|Refer to all of the words starting from n, but omit the last word|

### Modifiers

Placed after the word designator, multiple modifiers can be used a the same time.

|Modifier|Description|
|--|--|
|`:p`|Print the command instead and add it to the command history|
|`:h`|Remove a trailing pathname component, leaving only the head|
|`:t`|Remove all leading pathname components, leaving the tail|
|`:r`|Remove a trailing suffix of the form _.suffix_, leaving the basename|
|`:e`|Remove all but the trailing suffix|
|`:q`|Quote the substituted words, escaping further substitutions|
|`:x`|Quote the substituted words, but break into words at blanks|
|`:s/`_str_`/`_str_`/`|Substitute first occurrence of the first string with the second|
|`:&`|Repeat the previous substitution|
|`:g`/`:a`|Cause changes to be applied over the entire event line|
|`:G`|Apply the following `s` modifier once to each word in the event|

## Special Directories

|Name|Description|
|--|--|
|`.`|Current folder|
|`..`|Parent folder|
|`-`|Previous folder|
|`~`|Home folder|

## Special Variables

|Variable|Description|
|--|--|
|`$IFS`|Internal field separator<br />Contains characters that split shell words, typically includes the space, tab, and the newline|
|`$`_n_<br />`$(`_nn..._`)`|Positional Parameter<br />Assigned from the shell’s arguments when it is invoked, starting from one|
|`$*`|All positional parameters separated by first character of `$IFS`, `$1` `$2` `$3` ...|
|`$@`|All positional parameters, `{$1, $2, $3 ...}`|
|`$#`|Number of positional parameters|
|`$?`|Most recent foreground pipeline exit status|
|`$-`|Current options set for the shell|
|`$$`|Process ID of the current shell (not subshell)|
|`$!`|Process ID of the most recent background job|
|`$0`|Name of the shell or shell script|
|`$_`|Last argument of the previous command, on startup it is set to the absolute path of the current shell or shell script|

## Escape Characters

|Escape Char|Description|
|--|--|
|`\ `|space character|
|`\a`|alert (bell)|
|`\b`|backspace|
|`\e`/`\E`|escape|
|`\f`|form feed|
|`\n`|newline|
|`\r`|carriage return|
|`\t`|horizontal tab|
|`\v`|vertical tab|
|`\\`|backslash|
|`\'`|single quote|
|`\"`|double quote|
|`\?`|question mark|
|`\`_nnn_|The eight-bit character whose value is the octal value _nnn_ (one to three octal digits)|
|`\x`_HH_|The eight-bit character whose value is the hexadecimal value _HH_ (one or two hex digits)|
|`\u`_HHHH_|The Unicode character whose value is the hexadecimal value _HHHH_ (one to four hex digits)|
|`\U`_HHHHHHHH_|The Unicode character whose value is the hexadecimal value _HHHHHHHH_ (one to eight hex digits)|
|`\c`_char_|A control-_char_ character|

