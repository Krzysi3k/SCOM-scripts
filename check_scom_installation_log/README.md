-checks on remote machines if installation completed succesfully (info from SCOM installation log)

SCOM logs are located in: %LocalAppData%\SCOM\Logs\

how to run:
```batch
cd /d "%~dp0"
powershell.exe -file .\check_log.ps1
```