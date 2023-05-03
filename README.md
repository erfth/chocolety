# chocolety-defaul-apps

STEP 1:

`Set-ExecutionPolicy Bypass -Scope Process`

STEP 2:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`

STEP 3:
```
choco install chocolatey-core.extension --version 1.4.0 -y
choco install chocolatey-windowsupdate.extension --version 1.0.5 -y
choco install microsoft-teams.install --version 1.6.00.6754 -y
choco install notepadplusplus.install --version 8.5.2 -y
choco install 7zip.install --version 22.1 -y
choco install vlc --version 3.0.18 -y
choco install winscp.install --version 5.21.8 -y
choco install powertoys --version 0.68.1 -y
choco install brave --version 1.50.121 -y
choco install telegram.install --version 4.8.0 -y
choco install discord.install --version 1.0.9005 -y
choco install mobaxterm --version 23.0.0 -y
