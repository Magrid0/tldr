# expac

> Uno strumento di estrazione dati per database alpm, che offre flessibilità simile a printf per utilità basate su pacman.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://github.com/falconindy/expac#name>.

- Elenca le dipendenze di un pacchetto:

`expac {{[-S|--sync]}} '%D' {{pacchetto}}`

- Elenca le dipendenze opzionali di un pacchetto:

`expac {{[-S|--sync]}} "%o" {{pacchetto}}`

- Elenca la dimensione di download dei pacchetti in MiB:

`expac {{[-S|--sync]}} {{[-H|--humansize]}} M '%k\t%n' {{pacchetto1 pacchetto2 ...}}`

- Elenca i pacchetti contrassegnati per l'aggiornamento con la loro dimensione di download:

`expac {{[-S|--sync]}} {{[-H|--humansize]}} M '%k\t%n' $(pacman -Qqu) | sort {{[-sh|--sort --human-numeric-sort]}}`

- Elenca i pacchetti installati esplicitamente con le loro dipendenze opzionali:

`expac {{[-d|--delim]}} '\n\n' {{[-l|--listdelim]}} '\n\t' {{[-Q|--query]}} '%n\n\t%O' $(pacman -Qeq)`
