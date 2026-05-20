# audit2why

> Spiega i rifiuti SELinux dai log di audit.
> Parte del pacchetto `policycoreutils-python-utils`.
> Vedi anche: `audit2allow`, `ausearch`, `sealert`.
> Maggiori informazioni: <https://manned.org/audit2why>.

- Spiega il rifiuto SELinux più recente:

`sudo audit2why`

- Spiega i rifiuti SELinux da un file di log di audit specifico:

`sudo audit2why {{[-i|--input]}} {{path/to/audit.log}}`

- Spiega tutti i rifiuti SELinux dal log di audit:

`sudo ausearch {{[-m|--message]}} avc | audit2why`

- Spiega i rifiuti per un servizio specifico:

`sudo ausearch {{[-m|--message]}} avc {{[-c|--comm]}} {{nome_servizio}} | audit2why`
