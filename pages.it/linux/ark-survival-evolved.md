# ARK: Survival Evolved

> Crea e avvia un server ARK: Survival Evolved headless.
> Maggiori informazioni: <https://ark.wiki.gg/wiki/Server_configuration>.

- Avvia il server con una mappa specifica:

`{{path/to}}/ShooterGameServer {{TheIsland}}`

- Avvia il server con un nome sessione specifico, password del server e password amministratore:

`{{path/to}}/ShooterGameServer {{TheIsland}}?SessionName={{nome_sessione}}?ServerPassword={{password_server}}?ServerAdminPassword={{password_admin}}`

- Avvia il server con una porta specifica e imposta un numero massimo di giocatori:

`{{path/to}}/ShooterGameServer {{TheIsland}}?Port={{7777}}?MaxPlayers={{1..70}}`

- Abilita PvE e disabilita PvP:

`{{path/to}}/ShooterGameServer {{TheIsland}}?ServerPVE=true`

- Imposta un moltiplicatore per scalare la difficoltà del server, influenzando il livello massimo delle creature selvatiche:

`{{path/to}}/ShooterGameServer {{TheIsland}}?DifficultyOffset={{1.0}}`

- Abilita un evento specifico:

`{{path/to}}/ShooterGameServer {{TheIsland}} -ActiveEvent={{Summer}}`

- Abilita il download, l'installazione e l'aggiornamento automatico delle mod (solo Steam):

`{{path/to}}/ShooterGameServer {{TheIsland}} -automanagedmods`

- Abilita il crossplay tra Steam e Epic Games Store:

`{{path/to}}/ShooterGameServer {{TheIsland}} -crossplay -PublicIPForEpic={{indirizzo_ip}}`
