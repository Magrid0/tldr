# vgs

> Mostra informazioni sui volume group.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/vgs>.

- Mostra informazioni sui volume group:

`sudo vgs`

- Mostra tutti i volume group:

`sudo vgs {{[-a|--all]}}`

- Cambia la visualizzazione predefinita per mostrare più dettagli:

`sudo vgs {{[-v|--verbose]}}`

- Mostra solo campi specifici:

`sudo vgs {{[-o|--options]}} {{nome_campo_1,nome_campo_2,...}}`

- Aggiungi campo alla visualizzazione predefinita:

`sudo vgs {{[-o|--options]}} +{{nome_campo}}`

- Sopprime la riga di intestazione:

`sudo vgs --noheadings`

- Usa un separatore per separare i campi:

`sudo vgs --separator =`
