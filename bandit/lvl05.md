# username
bandit5

# password
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

# steps
locate the human readable non executable file of size 1033 bytes, in the "inhere" directory

```
ls
cd inhere
find . -size 1033c ! -executable
cat ./maybehere07/.file2
```