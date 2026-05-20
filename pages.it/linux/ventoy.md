# ventoy

> Uno strumento per creare unità USB avviabili usando file ISO.
> Maggiori informazioni: <https://www.ventoy.net/en/doc_start.html#doc_linux_cli>.

- Installa Ventoy su un'unità specifica con le impostazioni predefinite:

`sudo ventoy -i {{/dev/sdX}}`

- Installa Ventoy con stile di partizione GPT invece di MBR:

`sudo ventoy -i -g {{/dev/sdX}}`

- Installa Ventoy con stile di partizione GPT, un'etichetta di partizione personalizzata e secure boot disabilitato:

`sudo ventoy -i -g -S -L {{NOME_ETICHETTA}} {{/dev/sdX}}`

- Installa Ventoy e riserva spazio alla fine del disco:

`sudo ventoy -i -r {{DIMENSIONE_MB}} {{/dev/sdX}}`

- Forza l'installazione di Ventoy (sovrascrive l'installazione esistente):

`sudo ventoy -I {{/dev/sdX}}`

- Aggiorna Ventoy su un'unità:

`sudo ventoy -u {{/dev/sdX}}`

- Mostra informazioni su Ventoy per un'unità:

`sudo ventoy -l {{/dev/sdX}}`

- Prova l'installazione non distruttiva se possibile (Ventoy non riformatterà il disco):

`sudo ventoy -i -n {{/dev/sdX}}`
