# blastn

> BLAST nucleotide-nucleotide.
> Maggiori informazioni: <https://www.ncbi.nlm.nih.gov/books/NBK279684/table/appendices.T.blastn_application_options/>.

- Allinea due o più sequenze usando megablast (predefinito), con soglia e-value di 1e-9, formato di output pairwise (predefinito):

`blastn -query {{query.fa}} -subject {{subject.fa}} -evalue {{1e-9}}`

- Allinea due o più sequenze usando blastn:

`blastn -task blastn -query {{query.fa}} -subject {{subject.fa}}`

- Allinea due o più sequenze, formato di output tabulare personalizzato, output su file:

`blastn -query {{query.fa}} -subject {{subject.fa}} -outfmt '{{6 qseqid qlen qstart qend sseqid slen sstart send bitscore evalue pident}}' -out {{output.tsv}}`

- Cerca in database nucleotidici usando una query nucleotidica, 16 thread (CPU) per la ricerca BLAST, con un massimo di 10 sequenze allineate da mantenere:

`blastn -query {{query.fa}} -db {{path/to/blast_db}} -num_threads {{16}} -max_target_seqs {{10}}`

- Cerca nel database nucleotidico non ridondante remoto usando una query nucleotidica:

`blastn -query {{query.fa}} -db {{nt}} -remote`

- Mostra aiuto (usa `-help` per aiuto dettagliato):

`blastn -h`
