# 0x03. Shell, init files, variables and expansions

This project covers basic concepts of shell variable handling and script customization in the Linux environment.

## What I learned

- How to create and use shell aliases
- The difference between local and global (environment) variables
- Modifying the `PATH` variable
- Performing arithmetic operations in shell scripts
- Printing shell variables and functions

## Task List

| File                       | Description                                                |
|----------------------------|------------------------------------------------------------|
| `0-alias`                  | Creates an alias `ls='rm *'`                               |
| `1-hello_you`              | Prints `hello <user>` using the current Linux username     |
| `2-path`                   | Adds `/action` to the end of the `PATH` variable           |
| `3-paths`                  | Counts and prints the number of directories in `PATH`      |
| `4-global_variables`       | Prints all environment variables                           |
| `5-local_variables`        | Prints local variables, environment variables, and functions |
| `6-create_local_variable`  | Creates a local variable `BEST="School"`                   |
| `7-create_global_variable` | Creates a global variable `BEST="School"`                  |
| `8-true_knowledge`         | Adds 128 to the value of the `TRUEKNOWLEDGE` variable      |
| `9-divide_and_rule`        | Divides `POWER` by `DIVIDE`                                |
| `10-love_exponent_breath`  | Calculates `BREATH` raised to the power of `LOVE`          |

---

## Usage

All scripts are written in Bash. You can run or source them depending on their purpose:

```bash
./script-name     # for executable scripts
source script-name # for modifying current shell environment (e.g., aliases, PATH)
