# isosize

> Mostra la dimensione di un file ISO.
> Maggiori informazioni: <https://manned.org/isosize>.

- Mostra la dimensione di un file ISO:

`isosize {{path/to/file.iso}}`

- Mostra il conteggio dei blocchi e la dimensione dei blocchi di un file ISO:

`isosize {{[-x|--sectors]}} {{path/to/file.iso}}`

- Mostra la dimensione di un file ISO divisa per un dato numero (utilizzabile solo quando --sectors non è specificato):

`isosize {{[-d|--divisor]}} {{number}} {{path/to/file.iso}}`
