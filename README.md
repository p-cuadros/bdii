# Base de Datos II

Prerequisitos

1. Open a Powershell terminal in administrator mode.

2. Intall Chocolatey (https://chocolatey.org/install)

´´´
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
´´´

3. Install Windows components (https://docs.microsoft.com/en-us/windows/wsl/install-manual)
´´´
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
´´´

4. Download and install WSL kernel update from https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

5. Set WSL version
´´´
wsl --set-default-version 2
´´´

6. Install ubuntu
´´´
choco install wsl-ubuntu-2204
´´´

7. Install Docker Desktop
´´´
choco install docker-desktop
´´´