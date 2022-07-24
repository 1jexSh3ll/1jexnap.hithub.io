---
date: 2022-03-04
update: 2022-03-04
status: Ongoing
categories:
directory: 
rating: 
title: Windows command
tags: [Cli Command Cheatsheet Windows Enumeration Exploitation]
---
# Windows command

## Enumerate Registry

### Enumerate Registry keys related to password information
```powershell
reg query HKLM /f password /t REG_SZ /s
reg query HKCU /f password /t REG_SZ /s
```

### Enumerate for PuTTY credentials in the Registry
```powershell
reg query HKCU\Software\SimonTatham\PuTTY\Sessions /t REG_SZ /s
```
