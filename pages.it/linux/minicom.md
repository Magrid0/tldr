# minicom

> Comunica con l'interfaccia seriale di un dispositivo.
> Vedi anche: `picocom`, `cu`, `tio`.
> Maggiori informazioni: <https://manned.org/minicom>.

- Apre una porta seriale specifica:

`sudo minicom {{[-D|--device]}} {{/dev/ttyXYZ}}`

- Apre una porta seriale specifica con un dato baud rate:

`sudo minicom {{[-D|--device]}} {{/dev/ttyXYZ}} {{[-b|--baudrate]}} {{115200}}`

- Entra nel menu di configurazione prima di comunicare con una data porta seriale:

`sudo minicom {{[-D|--device]}} {{/dev/ttyXYZ}} {{[-s|--setup]}}`

- Cattura l'output di una porta seriale in un file:

`sudo minicom {{[-D|--device]}} {{/dev/ttyXYZ}} {{[-C|--capturefile]}} {{path/to/file}}`

- Esce da minicom:

`<Ctrl a><x><Enter>`

- Mostra aiuto:

`minicom {{[-h|--help]}}`
