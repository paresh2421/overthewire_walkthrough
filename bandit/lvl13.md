# username
bandit13

# password
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

# steps
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14.

```
scp -P 2220 bandit13@bandit.labs.overthewire.org:~/sshkey.private .
chmod 600 sshkey.private
ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
cat /etc/bandit_pass/bandit14
```