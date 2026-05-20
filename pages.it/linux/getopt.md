# getopt

> Analizza argomenti della riga di comando.
> Maggiori informazioni: <https://manned.org/getopt>.

- Analizza i flag opzionali `verbose`/`version` con abbreviazioni:

`getopt {{[-o|--options]}} vV {{[-l|--longoptions]}} verbose,version -- --version --verbose`

- Aggiunge un'opzione `--file` con un argomento obbligatorio con abbreviazione `-f`:

`getopt {{[-o|--options]}} f: {{[-l|--longoptions]}} file: -- --file=somefile`

- Aggiunge un'opzione `--verbose` con un argomento opzionale con abbreviazione `-v`, e passa un parametro non-opzione `arg`:

`getopt {{[-o|--options]}} v:: {{[-l|--longoptions]}} verbose:: -- --verbose arg`

- Accetta un flag `-r` e `--verbose`, un'opzione `--accept` con un argomento opzionale e aggiunge un'opzione `--target` con un argomento obbligatorio con abbreviazioni:

`getopt {{[-o|--options]}} rv::s::t: {{[-l|--longoptions]}} verbose,source::,target: -- -v --target target`
