# Installazione Spicetify
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/nicola02nb/SpicetifyInstall/blob/main/README.md)

Copia tutto e Incolla su Powershell

## Aprire powershell e incollare i seguenti comandi:

### 1) Download, installazione e avvio di spicetify:
```bash
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex`
spicetify backup apply -Y
```

### 2) Scaricare l'ad-blocker con il seguente comando:
```bash
Invoke-WebRequest -Uri https://raw.githubusercontent.com/CharlieS1103/spicetify-extensions/main/adblock/adblock.js -OutFile ~\appdata\roaming\spicetify\Extensions\adblock.js
```

### 3) Abilitare l'ad-blocker con i seguenti comandi:
```bash
spicetify config extensions adblock.js
spicetify apply
```
