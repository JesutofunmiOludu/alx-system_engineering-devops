# 0x03. Shell Variables, Expansions, and Arithmetic

This repository contains a series of Bash scripts that cover basic and advanced shell operations, including variables, environment variables, aliases, arithmetic, and expansions. Each task demonstrates fundamental shell scripting skills required for Linux system programming and DevOps tasks.

## Repository

- **GitHub Repository:** [alx-system_engineering-devops](https://github.com/yourusername/alx-system_engineering-devops)
- **Directory:** `0x03-shell_variables_expansions`

---

## Tasks Overview

### 0. Alias
- **File:** `0-alias`
- **Description:** Creates an alias `ls` that executes `rm *`.  
- **Example Usage:**
  ```bash
  julien@ubuntu:/tmp/0x03$ ls
  0-alias file1 file2
  julien@ubuntu:/tmp/0x03$ source ./0-alias
  julien@ubuntu:/tmp/0x03$ ls
  julien@ubuntu:/tmp/0x03$
1. Hello You
File: 1-hello_you

Description: Prints hello followed by the current Linux user.

Example Usage:

bash
Copy code
julien@ubuntu:/tmp/0x03$ ./1-hello_you
hello julien
2. The Path to Success
File: 2-path

Description: Adds /action to the end of the $PATH environment variable.

Example Usage:

bash
Copy code
julien@ubuntu:/tmp/0x03$ source ./2-path
julien@ubuntu:/tmp/0x03$ echo $PATH
...:/snap/bin:/action
3. Count Directories in PATH
File: 3-paths

Description: Counts the number of directories in $PATH.

Example Usage:

bash
Copy code
julien@ubuntu:/tmp/0x03$ . ./3-paths
11
4. Global Variables
File: 4-global_variables

Description: Lists all environment variables.

5. Local Variables
File: 5-local_variables

Description: Lists all local variables, environment variables, and shell functions.

6. Create a Local Variable
File: 6-create_local_variable

Description: Creates a local variable BEST with value School.

7. Create a Global Variable
File: 7-create_global_variable

Description: Creates a global variable BEST with value School.

8. True Knowledge
File: 8-true_knowledge

Description: Prints the sum of 128 and the value stored in TRUEKNOWLEDGE.

Example Usage:

bash
Copy code
export TRUEKNOWLEDGE=1209
./8-true_knowledge
1337
9. Divide and Rule
File: 9-divide_and_rule

Description: Prints the result of POWER / DIVIDE.

10. Love Exponent Breath
File: 10-love_exponent_breath

Description: Prints the result of BREATH raised to the power of LOVE.

11. Binary to Decimal
File: 11-binary_to_decimal

Description: Converts a binary number stored in BINARY to decimal.

12. Combinations
File: 12-combinations

Description: Prints all possible combinations of two lowercase letters, excluding oo.

Constraints: Maximum 64 characters in the script.

13. Print Float
File: 13-print_float

Description: Prints a number stored in NUM with two decimal places.

Notes
All scripts are written in Bash.

Some scripts require environment variables to be set before execution.

Scripts should be run with source when they modify environment variables in the current shell.

Focus on practicing shell expansions, variable scopes, arithmetic, and aliases.

Author
Engr Laughter Oludu

#License
This project is for learning purposes as part of the ALX System Engineering & DevOps curriculum.

pgsql
Copy code

If you want, I can also create a **more visually appealing version** with **table format for tasks, files, and descriptions**, which makes it much easier to scan.  

Do you want me to do that?
