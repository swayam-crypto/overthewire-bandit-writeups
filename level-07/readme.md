# Bandit Level 6 → 7 Writeup

## Goal
The password for the next level is stored in the file `data.txt` next to the word `millionth`.

## Commands Used
`ls`, `grep`

## Steps
- Ran `ls` to list the files in the current directory and confirm that `data.txt` exists.
- Used `grep "millionth" data.txt` to search for the line in `data.txt` that contains the word `millionth`.
- Read the output of the command and noted the password printed next to `millionth`.

## Password Found
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
