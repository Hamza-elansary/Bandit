# Bandit Worgame Solutions :
## Bandit Level 11 ==> level 12
**Description**
- The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.

**open game**

- *user* : bandit11
- *password*  level 11 ==> level 12 : **7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4**
**Solutions 1**
-  Use the tr command to change the position of 13 characters.
`bandit11@bandit:~$ cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'` .

- **explanation**
    - `cat data.txt` Print output - Standard output.
    - `tr 'A-Za-z' 'N-ZA-Mn-za-m'` Move the letters 13 spaces.
## Commands you may need to solve this level
- `man`
- `man grep`
- `man sort`
- `man uniq`
- `man strings`
- `man base64`
- `man tr`
- `man tar`
- `man grip`
- `man bzip2`
- `man xxd`
## Lessons Learned
- Understanding how 'tr' works and attempting to exploit it to decrypt the Caesar cipher using cell 13
## ٌResearch
- To understand how rot13 works, [click here](https://en.wikipedia.org/wiki/ROT13).
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)

