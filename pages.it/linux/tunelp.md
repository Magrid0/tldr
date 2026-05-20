# tunelp

> Imposta vari parametri per dispositivi di porta parallela per risolvere problemi o per migliorare le prestazioni.
> Parte di `util-linux`.
> Maggiori informazioni: <https://manned.org/tunelp>.

- Controlla lo stato di un dispositivo di porta parallela:

`tunelp {{[-s|--status]}} {{/dev/lp0}}`

- Reimposta una porta parallela specifica:

`tunelp {{[-r|--reset]}} {{/dev/lp0}}`

- Usa un IRQ specifico per un dispositivo, ciascuno rappresentante una linea di interrupt:

`tunelp {{[-i|--irq]}} 5 {{/dev/lp0}}`

- Prova un dato numero di volte a inviare un carattere alla stampante prima di attendere per un dato tempo:

`tunelp {{[-c|--chars]}} {{volte}} {{[-t|--time]}} {{tempo_in_centisecondi}} {{/dev/lp0}}`

- Abilita o disabilita l'interruzione su errore (disabilitata per impostazione predefinita):

`tunelp {{[-a|--abort]}} {{on|off}}`
