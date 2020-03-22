# Chocolatey

<https://chocolatey.org/>

## Install Chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
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

choco install cpu-z.install -y
choco install gpu-z -y
choco install hwmonitor -y
choco install hwinfo.install -y
choco install windirstat -y

choco install 7zip.install -y
choco install notepadplusplus.install -y
choco install beyondcompare -y
choco install postman -y
choco install fiddler -y

choco install azure-cli -y
choco install powershell-core -y
choco install git.install -y
choco install nodejs-lts -y

choco install vscode -y
choco install azure-data-studio -y
choco install sql-server-management-studio -y
choco install microsoftazurestorageexplorer -y

choco install resharper -y
choco install dotpeek -y

choco install gimp -y

choco install putty -y

choco install powertoys -y

choco install lili.install -y   # LinuxLive USB Creator
```
