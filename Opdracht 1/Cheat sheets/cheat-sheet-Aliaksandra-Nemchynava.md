# Cheat sheets en checklists

> Student: Aliaksandra Nemchynava

## Basiscommando's

| Taak | Commando |
|------|---------|
|Het installeert een pakket.| `winget install <appname>`|
|Het toont een lijst van geïnstalleerde software. Inclusief pakketten die niet door WinGet beheerd wordt.| `winget list`|
|Het toont de pad waarin je je bevind. | `(Get-Item -Path ".").Name`|
|Een lijst tonen van de software die nu geïnstalleerd is via WinGet.|`winget list`|
|Alle packages die nu geïnstalleerd zijn bijwerken tot de laatste versie.| `winget upgrade --all`|
|Bepaalde package die nu geïnstalleerd zijn bijwerken tot de laatste versie|`winget upgrade --id "PackageID" `|
|Via de console een package opzoeken.|`winget search "pakketnaam"`|
|Een geïnstalleerd pakket verwijderen.|`winget uninstall "pakketnaam"`|