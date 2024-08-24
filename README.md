# extra-cmd (v0.1)
 Extra Tools and Themes for CMD (Command Prompt) for Windows

# Configuration
 [How to run a command on command prompt startup in Windows](https://stackoverflow.com/questions/17404165/how-to-run-a-command-on-command-prompt-startup-in-windows)
```batch
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun ^
  /t REG_EXPAND_SZ /d "%"USERPROFILE"%\profile.cmd" /f
```