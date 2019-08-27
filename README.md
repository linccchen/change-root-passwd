# change-root-passwd
Write the ip, ssh port, account number, old password and new password of the cloud host that needs to be operated to the hosts.txt file. Each line represents a host.

example

```
10.0.0.1 22 root old_passwd new_passwd
```

Then execute

```
chmod +x batch-chapasswd.py chpasswd.exp
./batch-chpasswd.py
```

IF running have error: /usr/bin/expect: bad interpreter: No such file or directory ,so you need install software

```
yum install tcl-devel
yum install expect
```



