# slurmd

> Monitora tutte le attività in esecuzione sul nodo di calcolo, accetta attività, avvia attività e termina le attività in esecuzione su richiesta.
> Maggiori informazioni: <https://slurm.schedmd.com/slurmd.html>.

- Segnala il nodo riavviato quando il demone viene riavviato (usato per scopi di test):

`slurmd -b`

- Esegue il demone con il nome del nodo dato:

`slurmd -N {{nomenodo}}`

- Scrive i messaggi di log nel file specificato:

`slurmd -L {{percorso/del/file_output}}`

- Legge la configurazione dal file specificato:

`slurmd -f {{percorso/del/file}}`

- Mostra aiuto:

`slurmd -h`
