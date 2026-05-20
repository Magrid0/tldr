# wami

> Uno strumento open-source e facile da usare che raccomanda programmi adatti per attività.
> Maggiori informazioni: <https://github.com/evait-security/wami>.

- Trova risultati espansi in tutte le categorie dal lake e ordinali nell'ordine specificato:

`wami {{[-a|--show-all]}} {{[-S|--sort]}} {{asc|desc}} {{[-s|--search-all]}} {{stringa_ricerca}}`

- Cerca su GitHub per trovare risultati espansi, ordinati in ordine decrescente:

`wami {{[-a|--show-all]}} {{[-S|--sort]}} desc --github {{stringa_ricerca}}`

- Cerca su GitHub argomenti che corrispondono alla stringa di ricerca:

`wami --list-topics {{stringa_ricerca}}`

- Cerca nel lake uno strumento usato nei pentest per interrogare le credenziali predefinite e ordina i risultati in ordine decrescente:

`wami {{[-S|--sort]}} desc {{[-s|--search-all]}} pentest credential default`
