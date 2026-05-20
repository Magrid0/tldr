# systemd-cgls

> Mostra il contenuto della gerarchia selezionata del control group Linux in un albero.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-cgls.html>.

- Mostra l'intera gerarchia dei control group sul sistema:

`systemd-cgls`

- Mostra un albero dei control group di uno specifico resource controller:

`systemd-cgls {{cpu|memory|io}}`

- Mostra la gerarchia dei control group di una o più unità systemd:

`systemd-cgls {{[-u|--unit]}} {{unità1 unità2 ...}}`
