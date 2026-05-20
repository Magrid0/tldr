# blastp

> BLAST proteina-proteina.
> Maggiori informazioni: <https://www.ncbi.nlm.nih.gov/books/NBK279684/table/appendices.T.blastp_application_options/>.

- Allinea due o più sequenze usando blastp, con soglia e-value di 1e-9, formato di output pairwise, output a schermo:

`blastp -query {{query.fa}} -subject {{subject.fa}} -evalue {{1e-9}}`

- Allinea due o più sequenze usando blastp-fast:

`blastp -task blastp-fast -query {{query.fa}} -subject {{subject.fa}}`

- Allinea due o più sequenze, formato di output tabulare personalizzato, output su file:

`blastp -query {{query.fa}} -subject {{subject.fa}} -outfmt '{{6 qseqid qlen qstart qend sseqid slen sstart send bitscore evalue pident}}' -out {{output.tsv}}`

- Cerca in database proteici usando una query proteica, 16 thread per la ricerca BLAST, con un massimo di 10 sequenze allineate da mantenere:

`blastp -query {{query.fa}} -db {{blast_database_name}} -num_threads {{16}} -max_target_seqs {{10}}`

- Cerca nel database proteico non ridondante remoto usando una query proteica:

`blastp -query {{query.fa}} -db {{nr}} -remote`

- Mostra aiuto (usa `-help` per aiuto dettagliato):

`blastp -h`
