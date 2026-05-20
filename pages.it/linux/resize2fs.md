# resize2fs

> Ridimensiona un filesystem ext2, ext3 o ext4.
> Non ridimensiona la partizione sottostante. Il filesystem potrebbe dover essere smontato prima, consulta la pagina man per maggiori dettagli.
> Maggiori informazioni: <https://manned.org/resize2fs>.

- Ridimensiona automaticamente un filesystem alla sua dimensione massima possibile:

`resize2fs {{/dev/sdXN}}`

- Ridimensiona il filesystem a una dimensione di 40G, mostrando una barra di progresso:

`resize2fs -p {{/dev/sdXN}} {{40G}}`

- Riduce il filesystem alla sua dimensione minima possibile:

`resize2fs -M {{/dev/sdXN}}`
