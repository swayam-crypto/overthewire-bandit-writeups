# Bandit Level 5 → 6 Writeup

## Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

## Commands Used
ls, cd and find

## Steps
as the information provided in the question we know that the file is human-readable, 1033 bytes in size and not executable
so with "find" command and its various operators this was the performed command 
"ls", "cd inhere", "find . -type f -size 1033c ! -executable", "cat ./maybehere07/-file2"

## Password Found
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

