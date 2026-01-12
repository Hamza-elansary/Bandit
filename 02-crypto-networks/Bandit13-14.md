# Bandit Worgame Solutions :
## Bandit Level 13 ==> level 14
**Description**
- The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Look at the commands that logged you into previous bandit levels, and find out how to use the key for this level.
**open game**
- *user* : bandit13
- *password*  level 13 ==> level 14 : **MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS**

**Solutions**
- Obtaining an SSH key from Bandit14
- Exit Bandit 13 and attempt to enter Bandit 14 using the ssh key.
```
┌──(billy㉿kali)-[~/Desktop]
└─$ ssh  bandit0@bandit.labs.overthewire.org -p 2220 -i sshkey.private 

```
-Login is the same as for previous levels, only adding -i to use the login key instead of the password.

## Commands you may need to solve this level

- `man ssh`
- `man scp`
- `man umask`
- `man chmod`
- `man cat`
- `man nc`
- `man install`

## Lessons Learned
- The benefit of this lesson is logging in using the SSH key. 
## ٌResearch
- Helpful Reading Material : [ٍٍSSH/OpenSSH/Keys](https://help.ubuntu.com/community/SSH/OpenSSH/Keys) 
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)

