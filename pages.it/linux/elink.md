# elink

> Cerca vicini precalcolati all'interno di un database o trova record associati in altri database.
> Fa parte del pacchetto `edirect`.
> Maggiori informazioni: <https://www.ncbi.nlm.nih.gov/books/NBK179288/>.

- Cerca in pubmed e trova sequenze correlate:

`esearch -db pubmed -query "{{selective serotonin reuptake inhibitor}}" | elink -target nuccore`

- Cerca nucleotide e trova biosample correlati:

`esearch -db nuccore -query "{{insulin [PROT] AND rodents [ORGN]}}" | elink -target biosample`
