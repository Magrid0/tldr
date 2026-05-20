# pacinfo

> Mostra informazioni sui pacchetti installati.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacinfo.pod>.

- Mostra informazioni su un pacchetto specifico:

`pacinfo {{nome_pacchetto}}`

- Disabilita i timeout a bassa velocità per i download:

`pacinfo --no-timeout {{nome_pacchetto}}`

- Mostra le dimensioni in byte e le date come timestamp Unix:

`pacinfo --raw {{nome_pacchetto}}`

- Mostra informazioni aggiuntive sul pacchetto:

`pacinfo --verbose {{nome_pacchetto}}`

- Mostra aiuto:

`pacinfo --help`

- Mostra versione:

`pacinfo --version`
