# Cheat sheets en checklists

> Student: Dupon Jarne

## Basiscommando's

| Taak                                                                                                        | Commando                                    |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| Maakt het mogelijk scripts uit te voeren op je systeem.                                                     | `Set-ExecutionPolicy Bypass -Scope Process` |
| Toon een lijst van de software die nu geïnstalleerd is via WinGet.                                          | `winget list`                               |
| Alle packages die nu geïnstalleerd zijn bijwerken tot de laatste versie.                                    | `winget upgrade -all`                       |
| Via de console een package opzoeken.                                                                        | `winget search [[-q] <query>] [<options>]`                             |
| Een geïnstalleerd pakket verwijderen.                                                                       | `winget uninstall "pakket"`                 |
| Een applicatie installeren via pakketid                                                                     | `winget install <pakketid>`                 |
| Geef een overzicht te zien val alle mogelijke commands van winget die je kan uitvoeren.                     | `winget --help`                             |
| Een versie van een pakket pinnen.Zorgt ervoor dat WinGet bij volgende update geen nieuwe versie installeert | `winget pin add --id --version`             |
