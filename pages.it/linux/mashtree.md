# mashtree

> Crea un albero veloce da genomi.
> Non crea una filogenia.
> Maggiori informazioni: <https://github.com/lskatz/mashtree#usage>.

- Metodo più veloce in mashtree per creare un albero da file fastq e/o fasta usando più thread, reindirizzando in un file newick:

`mashtree --numcpus {{12}} {{*.fastq.gz}} {{*.fasta}} > {{mashtree.dnd}}`

- Metodo più accurato in mashtree per creare un albero da file fastq e/o fasta usando più thread, reindirizzando in un file newick:

`mashtree --mindepth {{0}} --numcpus {{12}} {{*.fastq.gz}} {{*.fasta}} > {{mashtree.dnd}}`

- Metodo più accurato per creare un albero con valori di confidenza (nota che qualsiasi opzione per `mashtree` deve essere sul lato destro di `--`):

`mashtree_bootstrap.pl --reps {{100}} --numcpus {{12}} {{*.fastq.gz}} -- --min-depth {{0}} > {{mashtree.bootstrap.dnd}}`
