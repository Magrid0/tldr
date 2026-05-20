# lvs

> Mostra informazioni sui volumi logici.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/lvs>.

- Mostra informazioni sui volumi logici:

`sudo lvs`

- Mostra tutti i volumi logici:

`sudo lvs {{[-a|--all]}}`

- Cambia la visualizzazione predefinita per mostrare più dettagli:

`sudo lvs {{[-v|--verbose]}}`

- Mostra solo campi specifici:

`sudo lvs {{[-o|--options]}} {{field_name_1,field_name_2,...}}`

- Aggiunge un campo alla visualizzazione predefinita:

`sudo lvs {{[-o|--options]}} +{{field_name}}`

- Sopprime la riga di intestazione:

`sudo lvs --noheadings`

- Usa un separatore per separare i campi:

`sudo lvs --separator {{=}}`
