# dmenu

> Menu dinamico.
> Crea un menu da un input di testo con ogni elemento su una nuova riga.
> Maggiori informazioni: <https://manned.org/dmenu>.

- Mostra un menu con l'output del comando `ls`:

`{{ls}} | dmenu`

- Mostra un menu con elementi personalizzati separati da una nuova riga (`\n`):

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu`

- Fa scegliere all'utente tra più elementi e salva quello selezionato in un file:

`echo -e "{{red}}\n{{green}}\n{{blue}}" | dmenu > {{color.txt}}`

- Avvia dmenu su un monitor specifico:

`ls | dmenu -m {{1}}`

- Mostra dmenu nella parte inferiore dello schermo:

`ls | dmenu -b`
