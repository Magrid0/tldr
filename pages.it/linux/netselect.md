# netselect

> Test di velocità per scegliere un server di rete veloce.
> Maggiori informazioni: <https://manned.org/netselect>.

- Sceglie il server con la latenza più bassa:

`sudo netselect {{host_1 host_2 ...}}`

- Mostra la risoluzione dei nomi e le statistiche:

`sudo netselect -vv {{host_1 host_2 ...}}`

- Definisce il TTL massimo (time to live):

`sudo netselect -m {{10}} {{host_1 host_2 ...}}`

- Stampa gli `n` server più veloci tra gli host:

`sudo netselect -s {{n}} {{host_1 host_2 host_3 ...}}`

- Mostra aiuto:

`netselect`
