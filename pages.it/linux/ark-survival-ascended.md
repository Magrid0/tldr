# ARK: Survival Ascended

> Crea e avvia un server ARK: Survival Ascended headless.
> Maggiori informazioni: <https://ark.wiki.gg/wiki/Server_configuration>.

- Avvia il server con una mappa specifica:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}}`

- Avvia il server con un nome sessione specifico, password del server e password amministratore:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}}?SessionName={{nome_sessione}}?ServerPassword={{password_server}}?ServerAdminPassword={{password_admin}}`

- Avvia il server con una porta specifica e imposta un numero massimo di giocatori:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}} -port={{7777}} -WinLiveMaxPlayers={{1..70}}`

- Abilita PvE e disabilita PvP:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}}?ServerPVE=true`

- Imposta un moltiplicatore per scalare la difficoltà del server, influenzando il livello massimo delle creature selvatiche:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}}?DifficultyOffset={{1.0}}`

- Disabilita l'ottimizzazione dell'animazione delle creature per prevenire problemi di collisione:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}} -AlwaysTickDedicatedSkeletalMeshes`

- Abilita mod specifiche tramite il loro ID (separati da virgola):

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}} -mods={{id_mod1,id_mod2,...}}`

- Consenti connessioni da piattaforme specifiche:

`{{path/to}}/ArkAscendedServer {{TheIsland_WP}} -ServerPlatform={{PC+XSX+PS5}}`
