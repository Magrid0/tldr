# fonttools subset

> Genera sottoinsiemi di caratteri o ottimizza le dimensioni dei file.
> Maggiori informazioni: <https://fonttools.readthedocs.io/en/latest/subset/index.html>.

- Sottoinsieme di un file di caratteri TTF al blocco Unicode Basic Latin:

`fonttools subset {{path/to/font.ttf}} --unicodes=U+0000-007F`

- Cambia il tipo di file in WOFF2:

`fonttools subset {{path/to/font.ttf}} --unicodes=U+0000-007F --flavor=woff2`

- Mantiene solo le caratteristiche OpenType onum (oldstyle figures) e kern (kerning):

`fonttools subset {{path/to/font.ttf}} --unicodes=U+0000-007F --layout-features=onum,kern`

- Imposta il nome del file di output:

`fonttools subset {{path/to/font.ttf}} --unicodes=U+0000-007F --output-file={{path/to/subset.ttf}}`
