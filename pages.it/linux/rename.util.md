# rename

> Rinomina più file.
> ATTENZIONE: Questo comando sovrascriverà i file senza chiedere conferma a meno che non venga usata l'opzione di simulazione.
> Nota: Questa pagina si riferisce al comando del pacchetto `util-linux`.
> Maggiori informazioni: <https://manned.org/rename>.

- Rinomina file usando semplici sostituzioni (sostituisce `foo` con `bar` ovunque trovato):

`rename {{foo}} {{bar}} {{*}}`

- Simulazione - mostra quali rinomine avverrebbero senza eseguirle:

`rename {{[-vn|--verbose --no-act]}} {{foo}} {{bar}} {{*}}`

- Non sovrascrivere file esistenti:

`rename {{[-o|--no-overwrite]}} {{foo}} {{bar}} {{*}}`

- Cambia le estensioni dei file:

`rename {{.ext}} {{.bak}} {{*.ext}}`

- Antepone "foo" a tutti i nomi di file nella directory corrente:

`rename '' '{{foo}}' {{*}}`

- Rinomina un gruppo di file numerati in modo incrementale aggiungendo zeri fino a 3 cifre:

`rename {{foo}} {{foo00}} {{foo?}} && rename {{foo}} {{foo0}} {{foo??}}`
