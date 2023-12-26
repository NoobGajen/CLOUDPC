Certainly! Here's a README.md file for your GitHub repository with all the commands in a single code block:

## Installation Steps

1. Install Chocolatey using the following command:

```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco install winget
winget install --id Kotatogram.Kotatogram
winget install --id c0re100.qBittorrent-Enhanced-Edition



```

