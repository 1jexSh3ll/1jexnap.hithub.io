---
date: 2022-03-05
update: 2022-03-05
status: NotStarted/Ongoing/Completed
categories:
directory: 
rating: 
title: Linux command
tags: 
---
# Linux command



## User management

### add user to group
```bash
sudo usermod -a -G sudo user
```

### Check user group
```bash
groups
```

### Add user to sudoer files
```bash
sudo visudo
```


## Network management

### Tcpdump
```bash
sudo tcpdump -s 0 -An host 192.168.184.136 and port 514
```

## Misc

### Grep

```bash
sudo grep -iP "184.136" /var/log/remote/test_wind_log | grep -iP "Microsoft-Windows-Sysmon" | grep -iP "Feb 10"
```
