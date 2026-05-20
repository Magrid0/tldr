# trace-cmd record

> Cattura eventi di trace del kernel.
> Vedi anche: `trace-cmd list`, `trace-cmd report`.
> Maggiori informazioni: <https://manned.org/trace-cmd-record>.

- Registra un trace con un plugin specifico:

`sudo trace-cmd record -p {{plugin}}`

- Registra un trace di un eseguibile specifico:

`sudo trace-cmd record -F {{eseguibile}}`

- Registra un trace di una funzione specifica:

`sudo trace-cmd record -g {{funzione}}`

- Escludi una funzione specifica dal trace:

`sudo trace-cmd record -n {{funzione}}`

- Limita la profondità del grafico di chiamata della funzione:

`sudo trace-cmd record --max-graph-depth {{profondità}}`

- Registra un trace da un ID di processo specifico:

`sudo trace-cmd record -P {{pid}}`
