# pactrans

> Installa, rimuovi e aggiorna pacchetti ALPM.
> Vedi anche: `pacinstall`, `pacremove`.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pactrans.pod>.

- Installa un pacchetto da un repository:

`sudo pactrans --install {{nome_pacchetto}}`

- Rimuovi un pacchetto:

`sudo pactrans --remove {{nome_pacchetto}}`

- Aggiorna tutti i pacchetti installati:

`sudo pactrans --sysupgrade`

- Installa un file pacchetto:

`sudo pactrans --file {{percorso/del/pacchetto.pkg.tar.zst}}`

- Sostituisci un pacchetto installato localmente con uno da un repository:

`sudo pactrans local/{{pacchetto_da_rimuovere}} {{nome_repository}}/{{pacchetto_da_installare}}`

- Mostra cosa farebbe la transazione senza eseguirla:

`pactrans --print-only --install {{nome_pacchetto}}`
