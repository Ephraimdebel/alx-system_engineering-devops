

# 0x03-shell_variables_expansions

## 0-alias

This script creates an alias for the `ls` command.

- **Alias Name:** ls
- **Alias Value:** rm *

### Description

After sourcing this script with:

```bash
source ./0-alias
```
## 1-hello_you

This script prints "hello <current_user>", where <current_user> is the Linux user running the script.

Example:

```bash
$ ./1-hello_you
hello Ephraim
```
## 2-path

This script appends "/action" to the end of the PATH environment variable.

Example:

```bash
$ echo $PATH
/home/julien/bin:/usr/bin
$ source ./2-path
$ echo $PATH
/home/julien/bin:/usr/bin:/action

```
## 3-paths

This script counts the number of directories in the PATH environment variable.

Example:

```bash
$ echo $PATH
/home/julien/bin:/usr/bin:/bin
$ . ./3-paths
```
## 4-global_variables

This script lists all environment variables in the current shell.

Example:

```bash
$ source ./4-global_variables
HOME=/home/julien
USER=julien
PATH=/home/julien/bin:/usr/bin:/bin
...
```
## 5-local_variables

This script lists all local variables, global environment variables, and functions in the current shell.

Example:

```bash
$ . ./5-local_variables
BASH=/bin/bash
BASH_VERSION='4.3.46(1)-release'
...
## 6-create_local_variable

This script creates a **local variable** called BEST with value "School".

Example:

```bash
$ . ./6-create_local_variable
$ echo $BEST
School
```

## 6-create_local_variable

This script creates a **local variable** called BEST with value "School".

Example:

```bash
$ . ./6-create_local_variable
$ echo $BEST
School
```

## 8-true_knowledge

This script prints the result of adding 128 to the value stored in the environment variable TRUEKNOWLEDGE.

Example:

```bash
$ export TRUEKNOWLEDGE=1209
$ ./8-true_knowledge
1337
```
