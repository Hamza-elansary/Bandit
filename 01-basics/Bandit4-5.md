# Bandit Worgame Solutions :
## Bandit Level 4 ==> level 5
**Description**
- The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

**Solutions**
- Enter the file inhere
`cd inhere`

**open game**
- *usr* : bandit4
- *password*  level 4 ==> level 5 : **4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw**
- To search for file types, we use the `file` command
```bandit4@bandit:~/inhere$ file ./*
./-file00: data
./-file01: OpenPGP Public Key
./-file02: OpenPGP Public Key
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
```
- read the "-file07" file using cat
`cat ./-file07`



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

