# compseq

> Calcola la composizione di parole uniche in sequenze.
> Maggiori informazioni: <https://www.bioinformatics.nl/cgi-bin/emboss/help/compseq/>.

- Conta le frequenze osservate di parole in un file FASTA, fornendo i valori dei parametri con prompt interattivo:

`compseq {{path/to/file.fasta}}`

- Conta le frequenze osservate di coppie di aminoacidi da un file FASTA, salva l'output in un file di testo:

`compseq {{path/to/input_protein.fasta}} -word 2 {{path/to/output_file.comp}}`

- Conta le frequenze osservate di esanucleotidi da un file FASTA, salva l'output in un file di testo e ignora i conteggi nulli:

`compseq {{path/to/input_dna.fasta}} -word 6 {{path/to/output_file.comp}} -nozero`

- Conta le frequenze osservate di codoni in un particolare frame di lettura; ignorando qualsiasi conteggio sovrapposto (cioè sposta la finestra di una lunghezza parola di 3):

`compseq -sequence {{path/to/input_rna.fasta}} -word 3 {{path/to/output_file.comp}} -nozero -frame {{1}}`

- Conta le frequenze osservate di codoni con frame shift di 3 posizioni; ignorando qualsiasi conteggio sovrapposto (dovrebbe riportare tutti i codoni tranne il primo):

`compseq -sequence {{path/to/input_rna.fasta}} -word 3 {{path/to/output_file.comp}} -nozero -frame 3`

- Conta le triplette di aminoacidi in un file FASTA e le confronta con una precedente esecuzione di `compseq` per calcolare i valori di frequenza attesi e normalizzati:

`compseq -sequence {{path/to/human_proteome.fasta}} -word 3 {{path/to/output_file1.comp}} -nozero -infile {{path/to/output_file2.comp}}`

- Approssima il comando precedente senza un file preparato in precedenza, calcolando le frequenze attese utilizzando le frequenze di singole basi/residui nelle sequenze di input fornite:

`compseq -sequence {{path/to/human_proteome.fasta}} -word 3 {{path/to/output_file.comp}} -nozero -calcfreq`

- Mostra aiuto (usa `-help -verbose` per maggiori informazioni sui qualificatori associati e generali):

`compseq -help`
