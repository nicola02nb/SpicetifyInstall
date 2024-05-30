# Spicetify Installl
[![it](https://img.shields.io/badge/lang-it-green.svg)](https://github.com/nicola02nb/SpicetifyInstall/blob/main/README.it.md)

Copy all commands abd paste inside a Powershell

## Open Powershell and paste the following commands:

### 1) Download, installation and running Spicetify:
```bash
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex
spicetify backup apply -Y
```

### 2) Downloading the ad-blocker with the following commands:
```bash
Invoke-WebRequest -Uri https://raw.githubusercontent.com/rxri/spicetify-extensions/main/adblock/adblock.js -OutFile ~\appdata\roaming\spicetify\Extensions\adblock.js
```

### 3) Enabling the ad-blocker with the following commands:
```bash
spicetify config extensions adblock.js
spicetify apply
```
