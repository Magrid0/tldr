# update-alternatives

> Mantiene comodamente i collegamenti simbolici per determinare i comandi predefiniti.
> Maggiori informazioni: <https://manned.org/update-alternatives>.

- Aggiungi un collegamento simbolico:

`sudo update-alternatives --install {{percorso/del/symlink}} {{nome_comando}} {{percorso/del/binario_comando}} {{priorità}}`

- Configura un collegamento simbolico per `java`:

`sudo update-alternatives --config {{java}}`

- Rimuovi un collegamento simbolico:

`sudo update-alternatives --remove {{java}} {{/opt/java/jdk1.8.0_102/bin/java}}`

- Mostra informazioni su un comando specificato:

`update-alternatives --display {{java}}`

- Mostra tutti i comandi e la loro selezione corrente:

`update-alternatives --get-selections`
