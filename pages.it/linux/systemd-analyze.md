# systemd-analyze

> Analizza e esegue il debug del gestore di sistema.
> Mostra i dettagli temporali del processo di avvio delle unità (servizi, mount point, dispositivi, socket).
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-analyze.html>.

- Stampa l'ultimo tempo di avvio del sistema:

`systemd-analyze`

- Elenca tutte le unità in esecuzione, ordinate per il tempo impiegato per inizializzarsi:

`systemd-analyze blame`

- Stampa un albero della catena critica in termini di tempo delle unità di avvio:

`systemd-analyze critical-chain`

- Crea un file SVG che mostra quando ogni servizio di sistema è stato avviato, evidenziando il tempo speso per l'inizializzazione:

`systemd-analyze plot > {{percorso/del/file.svg}}`

- Traccia un grafico delle dipendenze e lo converte in un file SVG:

`systemd-analyze dot | dot -T {{svg}} > {{percorso/del/file.svg}}`

- Mostra i punteggi di sicurezza delle unità in esecuzione:

`systemd-analyze security`

- Visualizza tutte le regole udev insieme senza mostrare i commenti:

`systemd-analyze cat-config udev/rules.d --tldr`
