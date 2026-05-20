# tmt run

> Esegue i passaggi di test di `tmt`. Per impostazione predefinita, vengono eseguiti tutti i passaggi.
> Maggiori informazioni: <https://tmt.readthedocs.io/en/stable/stories/cli.html#run>.

- Esegui tutti i passaggi di test per ogni piano:

`tmt run`

- Esegui solo il passaggio di discovery per mostrare quali test verrebbero eseguiti:

`tmt run discover {{[-v|--verbose]}}`

- Esegui tutti i passaggi e regola le opzioni del passaggio di provision:

`tmt run {{[-a|--all]}} provision {{[-h|--how]}} {{container}} {{[-i|--image]}} {{fedora:rawhide}}`

- Esegui solo i piani e i test selezionati:

`tmt run plan {{[-n|--name]}} {{/plan/name}} test {{[-n|--name]}} {{/test/name}}`

- Mostra i risultati dell'ultima esecuzione in un browser web:

`tmt run {{[-l|--last]}} report {{[-h|--how]}} {{html}} {{[-o|--open]}}`

- Esegui i test con il contesto fornito:

`tmt run {{[-c|--context]}} {{key=value}} {{[-c|--context]}} {{distro=fedora}}`

- Esegui test interattivamente (debug del codice di test nel mezzo di un test):

`tmt run {{[-a|--all]}} execute {{[-h|--how]}} {{tmt}} --interactive`

- Utilizza la modalità dry per vedere quali azioni verrebbero eseguite e usa la massima verbosità:

`tmt run {{[-n|--dry]}} {{[-vvv|--verbose --verbose --verbose]}}`
