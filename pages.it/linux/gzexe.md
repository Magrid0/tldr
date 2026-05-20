# gzexe

> Comprime file eseguibili mantenendoli eseguibili.
> Crea un backup del file originale, aggiungendo `~` al suo nome e crea uno script shell che decomprime ed esegue il binario al suo interno.
> Maggiori informazioni: <https://manned.org/gzexe>.

- Comprime un file eseguibile direttamente:

`gzexe {{path/to/executable}}`

- [d]ecomprime un file eseguibile compresso direttamente (es. converte lo script shell di nuovo in un binario non compresso):

`gzexe -d {{path/to/compressed_executable}}`
