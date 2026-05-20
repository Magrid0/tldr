# apparmor_parser

> Carica, compila e gestisce i profili di sicurezza AppArmor.
> Maggiori informazioni: <https://gitlab.com/apparmor/apparmor/-/wikis/manpage_apparmor_parser.8>.

- Carica un profilo nel kernel:

`sudo apparmor_parser {{[-a|--add]}} {{file_profilo}}`

- Sostituisce un profilo esistente:

`sudo apparmor_parser {{[-r|--replace]}} {{file_profilo}}`

- Rimuove un profilo dal kernel:

`sudo apparmor_parser {{[-R|--remove]}} {{nome_profilo}}`

- Carica un profilo in modalità complain (registra le violazioni ma non le blocca):

`sudo apparmor_parser {{[-C|--complain]}} {{[-r|--replace]}} {{path/to/profilo}}`

- Preprocessa un profilo (risolve gli include) e scrive la cache binaria in un file:

`apparmor_parser {{[-p|--preprocess]}} {{[-o|--ofile]}} {{path/to/output.cache}} {{[-Q|--skip-kernel-load]}} {{path/to/profilo}}`

- Preprocessa e stampa il profilo binario su `stdout` senza caricarlo:

`apparmor_parser {{[-p|--preprocess]}} {{[-S|--stdout]}} {{[-Q|--skip-kernel-load]}} {{path/to/profilo}}`

- Sostituisce un profilo saltando le letture della cache:

`sudo apparmor_parser {{[-r|--replace]}} {{[-T|--skip-read-cache]}} {{path/to/profilo}}`

- Sostituisce un profilo, ricostruisce la cache e la scrive in una directory personalizzata:

`sudo apparmor_parser {{[-r|--replace]}} {{[-W|--write-cache]}} {{[-L|--cache-loc]}} /{{path/to/cache}} {{path/to/profilo}}`
