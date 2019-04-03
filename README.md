SSH login without password

Usage:
```
./ssh_nopasswd user@8.8.8.8
```

All ssh options are supported.

Run script once, you can login with the same option without password using SSH. For other user, they still need password.

If not worked, remove '.ssh/authorized_keys' in server and try again.

Ref:
* http://www.linuxproblem.org/art_9.html
* https://serverfault.com/questions/116177/whats-the-difference-between-authorized-keys-and-authorized-keys2
