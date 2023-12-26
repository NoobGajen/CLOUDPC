Certainly! Here's a README.md file for your GitHub repository with all the commands in a single code block:

```markdown
# Chocolatey Package Installation

This set of commands is designed to facilitate the installation of Chocolatey and use it to install specific packages on a Windows system.

## Prerequisites

Ensure PowerShell execution policy allows script execution. Run the following command in PowerShell:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
```

Set the security protocol to enable TLS 1.2:

```powershell
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072
```

## Installation Steps

1. Install Chocolatey using the following command:

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

2. Install Windows Package Manager (winget):

```powershell
choco install winget
```

3. Install Kotatogram using winget:

```powershell
winget install --id Kotatogram.Kotatogram
```

4. Install qBittorrent Enhanced Edition using winget:

```powershell
winget install --id c0re100.qBittorrent-Enhanced-Edition
```

## Notes

- Ensure that you run these commands in an elevated PowerShell session (Run as Administrator).
- The provided commands assume an internet connection to download and install the necessary components.
```

Feel free to copy and paste this content into your README.md file on GitHub. If you have any additional information to add or customize, you can do so within this template.












Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install winget
winget install --id Kotatogram.Kotatogram
winget install --id c0re100.qBittorrent-Enhanced-Edition


