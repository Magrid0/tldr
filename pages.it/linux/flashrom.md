# flashrom

> Legge, scrive, verifica e cancella chip flash.
> Maggiori informazioni: <https://manned.org/flashrom>.

- Sonda il chip, assicurandosi che il cablaggio sia corretto:

`flashrom {{[-p|--programmer]}} {{programmer}}`

- Legge la flash e la salva in un file:

`flashrom {{[-p|--programmer]}} {{programmer}} {{[-r|--read]}} {{path/to/file}}`

- Scrive un file sulla flash:

`flashrom {{[-p|--programmer]}} {{programmer}} {{[-w|--write]}} {{path/to/file}}`

- Verifica la flash rispetto a un file:

`flashrom {{[-p|--programmer]}} {{programmer}} {{[-v|--verify]}} {{path/to/file}}`

- Sonda il chip utilizzando Raspberry Pi:

`flashrom {{[-p|--programmer]}} {{linux_spi:dev=/dev/spidev0.0}}`
