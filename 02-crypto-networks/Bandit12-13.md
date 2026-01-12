# Bandit Worgame Solutions :
## Bandit Level 12 ==> level 13
**Description**
- The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!).

**open game**
- *user* : bandit12
- *password*  level 12 ==> level 13 : **FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn**
**Solutions**

- Create a file in /tmp to work on it, copy the data.txt file using the `cp` command, and enter the file.
`bandit12@bandit:~$ mkdir -p /tmp/Hdump && cp data.txt /tmp/Hdump && cd /tmp/Hdump`

    - First, convert the file from hex dump format to the original format using the `xxd` command.
    - Second, identify the file type using the `file` command.
    - Third, convert the file format to match its actual type.
    - Fourth, extract the compressed file using the appropriate command.

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
- The key lesson learned: deal with multiple file types and exercise patience to reach the main file. 
## ٌResearch
- Helpful Reading Material : [Hex dump](https://en.wikipedia.org/wiki/Hex_dump) on Wikipediai
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)
