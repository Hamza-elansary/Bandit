# Bandit Worgame Solutions :
## Bandit Level 9 ==> level 10
**Description**
- The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
**open game**
- *user* : bandit8
- *password*  level 9 ==> level 10 : **FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey**
**Solutions 1**
- Open the `data.txt` file and look for the `human-readable` text string preceded by a number of = symbols.
`bandit9@bandit:~$ cat data.txt | grep -aE "[a-zA-Z0-9]{32}"`
- **explanation**
    - `cat data.txt` Open the data.txt file
    - This symbol `|` is used to send input from the first command `cat` to the next command `grep`.
    - `grep -aE "[a-zA-Z0-9]{32}"` Searching for a string within the binary output consisting of 32 symbols of lowercase and uppercase letters and numbers

**Solutions 2**
`bandit9@bandit:~$ strings data.txt | grep ===`
- **explanation**
    - `strings`Print strings using the `strings` command
    - `grep ===` Search for === within the text
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
Searching in binary files and obtaining human-readable text files.

## About Me
- github : **Hamza-elansary**
- linkdin : **Hamza el ansary**

