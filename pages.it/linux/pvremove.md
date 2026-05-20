# pvremove

> Rimuove le etichette LVM da uno o più volumi fisici.
> Maggiori informazioni: <https://manned.org/pvremove>.

- Rimuove un'etichetta LVM da un volume fisico:

`sudo pvremove {{/dev/sdXY}}`

- Mostra output dettagliato durante l'operazione:

`sudo pvremove {{[-v|--verbose]}} {{/dev/sdXY}}`

- Rimuove un'etichetta LVM senza chiedere conferma:

`sudo pvremove {{[-y|--yes]}} {{/dev/sdXY}}`

- Rimuove forzatamente un'etichetta LVM:

`sudo pvremove {{[-f|--force]}} {{/dev/sdXY}}`

- Mostra output in formato JSON:

`sudo pvremove --reportformat json {{/dev/sdXY}}`
