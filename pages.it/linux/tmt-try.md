# tmt try

> Sperimenta rapidamente con test e ambienti.
> Maggiori informazioni: <https://tmt.readthedocs.io/en/stable/stories/cli.html#try>.

- Sperimenta rapidamente con il metodo di provision predefinito (nessun test nella CWD):

`tmt try`

- Esegui un test nella directory di lavoro corrente:

`cd {{percorso/della/directory_di_test}} && tmt try`

- Utilizza un sistema operativo specifico:

`tmt try {{rhel-9}}`

- Seleziona sia un'immagine personalizzata che un metodo di provision:

`tmt try {{fedora@container}}`

- Seleziona test con filtro personalizzato:

`tmt try {{[-t|--test]}} {{feature}}`

- Prepara guest e attendi istruzioni:

`tmt try {{[-a|--ask]}}`

- Accedi direttamente al guest senza chiedere:

`tmt try {{[-l|--login]}}`

- Mostra aiuto:

`tmt try --help`
