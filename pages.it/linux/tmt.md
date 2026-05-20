# tmt

> Strumento di gestione dei test per creare, eseguire e fare debugging di test.
> Alcuni sottocomandi come `run`, `try`, ecc. hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://tmt.readthedocs.io/en/stable/examples.html>.

- Elenca test, piani e storie disponibili:

`tmt`

- Inizializza la struttura di file/progetto tmt:

`tmt init`

- Crea un nuovo test con un template e un collegamento:

`tmt test create {{[-t|--template]}} {{beakerlib}} --link {{verifies:issue#1234}}`

- Elenca test, piani o storie disponibili:

`tmt {{test|plan|story}} ls {{pattern}}`

- Mostra i metadati dettagliati del test nel contesto specificato:

`tmt {{[-c|--context]}} {{arch=aarch64}} test show`

- Convalida i file tmt rispetto alle specifiche:

`tmt lint`

- Utilizza un filtro:

`tmt tests ls {{[-f|--filter]}} {{tag:foo}} {{[-f|--filter]}} {{tier:0}}`

- Mostra aiuto:

`tmt --help`
