# Bandit Worgame Solutions :
## Bandit Level 7 ==> level 8
**Description**
- The password for the next level is stored in the file data.txt next to the word millionth
**open game**
- *user* : bandit7
- *password*  level 7 ==> level 8 : **dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc**
**Solutions**
- Open the `data.txt` file and search for the word `millionth`. You will find the `password` next to it.
- `bandit7@bandit:~$ cat data.txt | grep -i millionth`
- **explanation**
    - `cat data.txt` Reading the contents of the file
    - Symbol `|` Sends the output of the first command `cat` to the next command `grep`
    - `grep -i millionth` To search for a word in the middle of a file, disregarding the case of the letters.

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
Learn how to use the `grep` command to search for a word or text string within a file.
## About Me
- github : **Hamza-elansary**
- linkdin : **Hamza el ansary**


