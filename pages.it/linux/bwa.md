# bwa

> Strumento di allineamento Burrows-Wheeler.
> Mappatore di sequenze DNA brevi e a bassa divergenza contro un grande genoma di riferimento, come il genoma umano.
> Maggiori informazioni: <https://manned.org/bwa>.

- Indicizza il genoma di riferimento:

`bwa index {{path/to/reference.fa}}`

- Allinea letture single-end (sequenze) al genoma indicizzato usando 32 [t]hread e comprime il risultato per risparmiare spazio:

`bwa mem -t 32 {{path/to/reference.fa}} {{path/to/read_single_end.fq.gz}} | gzip > {{path/to/alignment_single_end.sam.gz}}`

- Allinea letture pair-end (sequenze) al genoma indicizzato usando 32 [t]hread e comprime il risultato per risparmiare spazio:

`bwa mem -t 32 {{path/to/reference.fa}} {{path/to/read_pair_end_1.fq.gz}} {{path/to/read_pair_end_2.fq.gz}} | gzip > {{path/to/alignment_pair_end.sam.gz}}`

- Allinea letture pair-end (sequenze) al genoma indicizzato usando 32 [t]hread con [M]arcatura dei hit divisi più corti come secondari per la compatibilità con il software Picard e comprime il risultato:

`bwa mem -M -t 32 {{path/to/reference.fa}} {{path/to/read_pair_end_1.fq.gz}} {{path/to/read_pair_end_2.fq.gz}} | gzip > {{path/to/alignment_pair_end.sam.gz}}`

- Allinea letture pair-end (sequenze) al genoma indicizzato usando 32 [t]hread con [C]ommenti FASTA/Q (es. BC:Z:CGTAC) aggiunti al risultato compresso:

`bwa mem -C -t 32 {{path/to/reference.fa}} {{path/to/read_pair_end_1.fq.gz}} {{path/to/read_pair_end_2.fq.gz}} | gzip > {{path/to/alignment_pair_end.sam.gz}}`
