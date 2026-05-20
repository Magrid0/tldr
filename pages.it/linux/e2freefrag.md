# e2freefrag

> Stampa le informazioni sulla frammentazione dello spazio libero per filesystem ext2/ext3/ext4.
> Maggiori informazioni: <https://manned.org/e2freefrag>.

- Controlla quanti blocchi liberi sono presenti come spazio libero contiguo e allineato:

`e2freefrag {{/dev/sdXN}}`

- Specifica la dimensione del [c]hunk in kilobyte per stampare quanti chunk liberi sono disponibili:

`e2freefrag -c {{dimensione_chunk_in_kb}} {{/dev/sdXN}}`
