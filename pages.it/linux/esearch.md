# esearch

> Esegue una nuova ricerca Entrez utilizzando termini in campi indicizzati.
> Fa parte del pacchetto `edirect`.
> Maggiori informazioni: <https://www.ncbi.nlm.nih.gov/books/NBK179288/>.

- Cerca nel database pubmed "selective serotonin reuptake inhibitor":

`esearch -db pubmed -query "{{selective serotonin reuptake inhibitor}}"`

- Cerca nel database protein usando una query e `regex`:

`esearch -db {{protein}} -query '{{Escherichia*}}'`

- Cerca nel database nucleotide per sequenze i cui metadati contengono insulina e roditori:

`esearch -db nuccore -query "{{insulin [PROT] AND rodents [ORGN]}}"`

- Mostra aiuto:

`esearch {{[-h|-help]}}`
