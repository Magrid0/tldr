# pvs

> Mostra informazioni sui volumi fisici.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/pvs>.

- Mostra informazioni sui volumi fisici:

`sudo pvs`

- Mostra volumi non fisici:

`sudo pvs {{[-a|--all]}}`

- Cambia la visualizzazione predefinita per mostrare più dettagli:

`sudo pvs {{[-v|--verbose]}}`

- Mostra solo campi specifici:

`sudo pvs {{[-o|--options]}} {{nome_campo_1,nome_campo_2,...}}`

- Aggiungi un campo alla visualizzazione predefinita:

`sudo pvs {{[-o|--options]}} +{{nome_campo}}`

- Sopprime la riga di intestazione:

`sudo pvs --noheadings`

- Usa un separatore per separare i campi:

`sudo pvs --separator {{carattere_speciale}}`
