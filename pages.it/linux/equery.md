# equery

> Visualizza informazioni sui pacchetti Portage.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Equery>.

- Elenca tutti i pacchetti installati:

`equery list '*'`

- Cerca pacchetti installati nell'albero di Portage e negli overlay:

`equery list -po {{pacchetto1 pacchetto2 ...}}`

- Elenca tutti i pacchetti che dipendono da un dato pacchetto:

`equery depends {{pacchetto}}`

- Elenca tutti i pacchetti da cui dipende un dato pacchetto:

`equery depgraph {{pacchetto}}`

- Elenca tutti i file installati da un pacchetto:

`equery files --tree {{pacchetto}}`
