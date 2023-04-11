# Windows-11-Tweaks

Windows 11 Tweaks for improved user experience

# Enable or Disable "Show more options" context menu using Command

Open Windows Terminal, and select Windows PowerShell or Command Prompt.

Copy and paste the command below you want into Windows Terminal, and press Enter.

```
DISABLE: ```reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve```

OR

ENABLE: ```reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f```
