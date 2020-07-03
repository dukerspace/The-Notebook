---
id: ubuntu
title: Ubuntu
type: docs
path: the-notebook/ubuntu
---

## Ubuntu
- uptime : check time use on computer

#### remove app
- sudo apt-get purge <name>
- sudo apt autoremove

#### switch to gui mode
- Ctrl + Alt + F7

#### check port used
```
sudo lsof -t -i:80
```

#### stop process by port
```
sudo kill `sudo lsof -t -i:80`
```

#### check disk
```
df -H
```

#### add user
- adduser <username>
```
adduser dukerspace
```

#### add root privileges
- visudo
```
user ALL=(ALL:ALL)ALL
```

#### remove user
- userdel <username>
```
userdel dukerspace
```

#### set timezone
```
sudo timedatectl set-timezone Asia/Bangkok
```

#### check timezone
```
timedatectl
timedatectl status | grep "Time zone"
```
