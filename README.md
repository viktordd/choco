# Chocolatey

<https://chocolatey.org/>

## Install Chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Useful Commands

```powershell
choco list -l
choco outdated
choco upgrade all -y
```

## Packages

```powershell
choco install googlechrome -y
choco install microsoft-teams -y
choco install slack -y

choco install cpu-z -y
choco install gpu-z -y
choco install hwmonitor -y
choco install hwinfo -y

choco install geforce-experience -y
choco install msiafterburner -y

choco install windirstat -y
choco install 7zip -y
choco install notepadplusplus -y
choco install beyondcompare -y
choco install postman -y
choco install fiddler -y

choco install azure-cli -y
choco install powershell-core -y
choco install git -y
choco install nodejs-lts -y

choco install vscode -y
choco install azure-data-studio -y
choco install sql-server-management-studio -y
choco install microsoftazurestorageexplorer -y
choco install python -y

choco install resharper -y
choco install dotpeek -y

choco install gimp -y

choco install putty -y

choco install powertoys -y

choco install etcher -y   # balena Etcher
choco install lili -y   # LinuxLive USB Creator
```
