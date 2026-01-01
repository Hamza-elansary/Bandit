# Bandit Worgame Solutions :
## Bandit Level 6 ==> level 7
**Description**
- The password for the next level is stored somewhere on the server and has all of the following properties:
**Rules**
```
    owned by user bandit7
    owned by group bandit6
    33 bytes in size
```
**open game**
- *usr* : bandit6
- *password*  level 6 ==> level 7 : **morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj**

**Solutions**
-Search for a file using the `find` command with the `rules` to access the file quickly and efficiently.
```
bandit6@bandit:/$ find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
```
- **explanation** 
    - `find / -type f` Search for a file in the entire system
    - `-user bandit7` owned by user bandit7
    - `-group bandit6` owned by group bandit6
    - `-size 33c` 33 bytes in size
    - `2>/dev/null` Send all errors to the tasks section

- Reading the file using the `cat` command
`bandit6@bandit:/$ cat /var/lib/dpkg/info/bandit7.password`

## Commands you may need to solve this level
- `man ls`
- `man cd`
- `man cat`
- `man file`
- `man du`
- `man find`
- `man grep`
## Lessons Learned
Learn how to use the `find` command to customize and filter the output to achieve the best result.
- Delve deeper into the file command with the `/` option to search the entire system
- Filter the search by properties `-user -group -size`
## About Me
- github : **Hamza-elansary**
- linkdin : **Hamza el ansary**


