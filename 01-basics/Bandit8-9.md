# Bandit Worgame Solutions :
## Bandit Level 8 ==> level 9
**Description**
- The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
**open game**
- *user* : bandit8
- *password*  level 8 ==> level 9 : **4CKMh1JI91bUIZZPXDqGanal4xvAg0JM**
**Solutions**
- Search for the unique password in the `data.txt` file.
`bandit8@bandit:~$ sort data.txt | uniq -u`
- **explanation**
    - `sort data.txt` View the contents of the `data.txt` file
    - This symbol `|` is used to send input from the first command `sort` to the next command `uniq`.
    - `uniq -u` To obtain the non-duplicate line 
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
View the file contents using the `sort` command and filter them to obtain the unique word using the `uniq` command.
## About Me
- github : **Hamza-elansary**
- linkdin : **Hamza el ansary**

