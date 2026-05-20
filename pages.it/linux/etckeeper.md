# etckeeper

> Tiene traccia dei file di configurazione di sistema in Git.
> Maggiori informazioni: <https://manned.org/etckeeper>.

- Imposta un repository Git ed esegue varie attività di configurazione (da eseguire da `/etc`):

`sudo etckeeper init`

- Commette tutte le modifiche in `/etc`:

`sudo etckeeper commit {{messaggio}}`

- Esegue comandi Git arbitrari:

`sudo etckeeper vcs {{status}}`

- Controlla se ci sono modifiche non commesse (restituisce solo un codice di uscita):

`sudo etckeeper unclean`

- Distrugge il repository esistente e interrompe il tracciamento delle modifiche:

`sudo etckeeper uninit`
