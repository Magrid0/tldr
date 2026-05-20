# nmon

> Uno strumento di amministrazione di sistema, ottimizzazione e benchmark.
> Maggiori informazioni: <https://manned.org/nmon>.

- Avvia `nmon`:

`nmon`

- Salva i record in un file ("-s 300 -c 288" per impostazione predefinita):

`nmon -f`

- Salva i record in un file con un totale di 240 misurazioni, prendendo 30 secondi tra ogni misurazione:

`nmon -f -s {{30}} -c {{240}}`
