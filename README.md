# Installazione Spicetify

Copia tutto e Incolla su Powershell

## Aprire powershell e incollare i seguenti comandi:

### 1) Download, installazione e avvio di spicetify:

`iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex`

`spicetify backup apply` #(durante l'esecuzione devi scrivere 'y' e poi premere invio)

### 2) Scaricare l'ad-blocker con il seguente comando:

`Invoke-WebRequest -Uri https://raw.githubusercontent.com/CharlieS1103/spicetify-extensions/main/adblock/adblock.js -OutFile ~\appdata\roaming\spicetify\Extensions\adblock.js`

### 3) Abilitare l'ad-blocker con i seguenti comandi:

`spicetify config extensions adblock.js`

`spicetify apply`
