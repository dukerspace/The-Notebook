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