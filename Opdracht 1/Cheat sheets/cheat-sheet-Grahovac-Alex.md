# Cheat sheets en checklists

> Student: Alex Grahovac 

## Basiscommando's

| Taak                                                  | Commando                        |
| ----------------------------------------------------- | ------------------------------- |
| Een lijst tonen van de software die nu geïnstalleerd is via WinGet| Winget list                      |                         
| Via de console een package opzoeken | winget search [[-q] \<query\>] [\<options\>] | 
| Om een applicatie te instaleren via winget | winget install \<appname\> |
|                                            |  winget install -e --id \<pakketid\>
| Alle packages die nu geïnstalleerd zijn bijwerken tot de laatste versie | winget upgrade --all |
| Dit schakelt de controle op digitale gehandtekende scripts uit voor de huidige PowerShell sessie, en maakt alle scripts uitvoerbaar. (ga je altijd moeten doen bij opnieuw starten van de shell) | Set-ExecutionPolicy Bypass -Scope Process|
| Een geïnstalleerd pakket verwijderen | winget uninstall [[-q] \<query\>...] [\<options\>] |
