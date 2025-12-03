# Bandit Level 5 → 6 Writeup

## Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

## Commands Used
ls, find, cat, cd

## Steps
- first did ls and found there were no files also not hidden files
- then performed a find method with different operands as per the question
- find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
- we used "-type" operator for finding the file type
- "-user" operator for finding the user bandit7
- "-group: operator for finding the group bandit6
- "-size" operator for finding file size of 33 and c for byte because CLI operates on blocks and 1 block = 512bytes
- "2>/dev/null" is used to ignore hidden file warning

## Password Found
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
