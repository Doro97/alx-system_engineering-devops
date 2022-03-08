# Shell Expansions and Variables
## Expansions
Expansion is the process in which a typed command is expanded into something else before the shell acts upon it.
### Types of expansions
#### 1. Brace expansion
Use to create multiple text strings from a pattern containing braces.Patterns to be brace expanded may contain a leading portion called a *preamble* and a trailing portion called a *postscript*. 
#### 2. Tilde expansion
The ~ character when  used at the beginning of a word, it expands into the name of the home directory of the named user, or if no user is named, the home directory of the current user.
#### 3. Shell parameter and variable expansion
The basic form of parameter expansion is "${PARAMETER}" or $PARAMETER

#### 4.Command substitution
Command substitution allows the output of a command to replace the command itself. Syntax : $(command) or `command`
#### 5.Arithmetic expansion
This uses the form:  $((expression)) where expression is an arithmetic expression consisting of values and arithmetic operators
#### 6.Process substitution
#### 7. Word splitting
#### 8. File name expansion

## Variables
### Creating Variables
To set a local variable in the shell, use:
VARNAME="value"
### Exporting Variables
export VARNAME="value"

## The *alias* Command	
The alias command makes it possible to launch any command or group of commands by entering a pre-set string 
Syntax in the bash shell: alias [-p] [name="value"] where 
*name* is the name of the new alias and *value* is the command(s) which it initiates
When used with no arguments and with or without the -p option, alias provides a list of aliases that are in effect for the current use.