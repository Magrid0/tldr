# uvcdynctrl

> Gestisce i controlli dinamici in uvcvideo.
> Maggiori informazioni: <https://manned.org/uvcdynctrl>.

- Elenca tutte le fotocamere disponibili:

`uvcdynctrl {{[-l|--list]}}`

- Usa un dispositivo specifico (default su `video0`):

`uvcdynctrl {{[-d|--device]}} {{nome_dispositivo}}`

- Elenca i controlli disponibili:

`uvcdynctrl {{[-c|--clist]}}`

- Imposta un nuovo valore di controllo (per valori negativi, usa `-- -valore`):

`uvcdynctrl {{[-s|--set]}} {{nome_controllo}} {{valore}}`

- Ottieni il valore corrente del controllo:

`uvcdynctrl {{[-g|--get]}} {{nome_controllo}}`

- Salva lo stato dei controlli correnti in un file:

`uvcdynctrl {{[-W|--save]}} {{nome_file}}`

- Carica lo stato dei controlli da un file:

`uvcdynctrl {{[-L|--load]}} {{nome_file}}`
