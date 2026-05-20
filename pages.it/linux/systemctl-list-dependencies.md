# systemctl list-dependencies

> Mostra l'albero delle dipendenze di un'unità in systemd.
> Vedi anche: `systemctl list-units`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-dependencies%20UNIT%E2%80%A6>.

- Mostra l'albero delle dipendenze di `default.target`:

`systemctl list-dependencies`

- Mostra l'albero delle dipendenze di un'unità specifica:

`systemctl list-dependencies {{unità}}`

- Include tutti i tipi di dipendenza (non solo `Requires=` e `Wants=`):

`systemctl list-dependencies {{unità}} {{[-a|--all]}}`

- Limita l'albero a un tipo di unità specifico:

`systemctl list-dependencies {{unità}} {{[-t|--type]}} {{service|socket|target|mount|...}}`

- Inverte la direzione per mostrare le unità che dipendono dall'unità specificata:

`systemctl list-dependencies {{unità}} --reverse`

- Stampa l'output senza intestazioni o piè di pagina (per script):

`systemctl list-dependencies {{unità}} --no-legend`
