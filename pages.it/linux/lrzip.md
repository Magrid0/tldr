# lrzip

> Un programma di compressione di file grandi.
> Vedi anche: `lrunzip`, `lrztar`, `lrzuntar`.
> Maggiori informazioni: <https://manned.org/lrzip>.

- Comprime un file con LZMA - compressione lenta, decompressione veloce:

`lrzip {{path/to/file}}`

- Comprime un file con BZIP2 - buon compromesso tra compressione e velocità:

`lrzip {{[-b|--bzip2]}} {{path/to/file}}`

- Comprime con ZPAQ - compressione estrema, ma molto lento:

`lrzip {{[-z|--zpaq]}} {{path/to/file}}`

- Comprime con LZO - compressione leggera, decompressione estremamente veloce:

`lrzip {{[-l|--lzo]}} {{path/to/file}}`

- Comprime un file e lo protegge con password/cifra:

`lrzip {{[-e|--encrypt]}} {{path/to/file}}`

- Sovrascrive il numero di thread del processore da usare:

`lrzip {{[-p|--threads]}} {{8}} {{path/to/file}}`
