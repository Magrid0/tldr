# cu

> Chiama un altro sistema e funge da terminale di connessione seriale o esegue trasferimenti di file senza controllo degli errori.
> Vedi anche: `picocom`, `minicom`, `tio`.
> Maggiori informazioni: <https://manned.org/cu>.

- Apre una porta seriale specificata:

`sudo cu {{[-l|--line]}} {{/dev/ttyXYZ}}`

- Apre una porta seriale specificata con un dato baud rate:

`sudo cu {{[-l|--line]}} {{/dev/ttyXYZ}} {{[-s|--speed]}} {{115200}}`

- Apre una porta seriale specificata con un dato baud rate e eco dei caratteri in locale (modalità half-duplex):

`sudo cu {{[-l|--line]}} {{/dev/ttyXYZ}} {{[-s|--speed]}} {{115200}} {{[-h|--halfduplex]}}`

- Apre una porta seriale specificata con un dato baud rate, parità e senza controllo di flusso hardware o software:

`sudo cu {{[-l|--line]}} {{/dev/ttyXYZ}} {{[-s|--speed]}} {{115200}} --parity={{even|odd|none}} {{[-f|--nortscts]}} --nostop`

- Esce dalla sessione `cu` quando in connessione:

`<Enter><~><.>`

- Mostra aiuto:

`cu --help`
