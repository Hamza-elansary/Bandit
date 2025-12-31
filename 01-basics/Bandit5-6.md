# Bandit Worgame Solutions :
## Bandit Level 5 ==> level 6
**Description**
- The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

**Rules**
```
    human-readable
    1033 bytes in size
    not executable
```
**open game**
- *usr* : bandit5
- *password*  level 5 ==> level 6 : **HWasnPhtq9AVKe0dmk45nxy20cvUa6EG**

**Solutions**
- Access the inhere file using the `cd` command.
`cd inhere`
- Search for the file using the `find` command.
```
bandit5@bandit:~$ find . -type f ! -executable -size 1033c
./inhere/maybehere07/.file2
```
- read file `.file2`
`bandit5@bandit:~$ cat ./inhere/maybehere07/.file2`
- Explanation of commands
Find a file in this folder that is a regular file type

`find . -type f`

not executable

`! -executable`

1033 bytes in size

`-size 1033c`


## Commands you may need to solve this level
- man : ls
- man : cd
- man : cat
- man : file
- man : du
- man : find

## About Me
- github : **Hamza-elansary**
- linkdin : **Hamza el ansary**

