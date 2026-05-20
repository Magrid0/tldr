# qrcp

> Uno strumento di trasferimento file.
> Maggiori informazioni: <https://github.com/claudiodangelis/qrcp#usage>.

- Invia file o directory:

`qrcp send {{path/to/file_or_directory1 path/to/file_directory2 ...}}`

- Riceve file:

`qrcp receive`

- Comprime il contenuto prima del trasferimento:

`qrcp send --zip {{path/to/file_or_directory}}`

- Usa una porta specifica:

`qrcp {{send|receive}} {{[-p|--port]}} {{port_number}}`

- Usa un'interfaccia di rete specifica:

`qrcp {{send|receive}} {{[-i|--interface]}} {{interface}}`

- Mantiene il server attivo:

`qrcp {{send|receive}} --keep-alive`
