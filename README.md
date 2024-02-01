# Minishell
<p align="center">
<img src="./minishell.png">
</p>
<p align="center">
<h4> As beautiful as a shell </h1>
</p>
</br>

## Description  
- The goal of Minishell was to create a mini version of bash, through the creation of a basic command interpreter. We learn about system calls, process manipulation, input/output redirection, and environment variables, while developing problem-solving skills, programming logic, and teamwork. This project was an opportunity to apply theoretical knowledge into a challenging practical application.
---
### Discription of mandatory part
We had to incorporate the following features:

- Display a promt while waiting for a new commmand.
- Have a working history.
- Find and launch executables (using the `PATH` variable or an absolute path).
- Handle `'` (single) and `"` (double) **quotes** like in bash.
- Implement **redirections** such as:
  - `<` redirect input.
  - `>` redirect output.
  - `<<` heredoc (doesn't affect history).
  - `>>` redirect output in append mode.
- Implement `|` (**pipes**).
- Handle **environment variables**.
- Handle `$?`.
- `ctrl-C`, `ctrl-D`, and `ctrl-\` should behave like in bash.
- Recreate the following **builtins**:
  - `echo` with option `-n`.
  - `cd` with only a relative or absolute path (we implemented the tilde shortcut "~").
  - `pwd` (no flags).
  - `export` (no flags).
  - `unset` (no flags).
  - `env` (no flags or arguments).
  - `exit` (no flags).

## Makefile rules

| Rule         |                 Description                             |
|:------------:|:-------------------------------------------------------:|
| `make`       | Compile the program.                                    |
| `make clean` | Remove every objects of compilation                     |
| `make fclean`| Do `clean` rule and remove the executable program       |
| `make re`    | Do `fclean` rule and compile the program mandatory      |

## Instalation 
### Clone the repository:
``` 
git clone https://github.com/LuMedeir/Minishell_42.git
cd minishell
```
### Run Minishell
```
make
./minishell
```
*to exit the program:*
```
exit
```
