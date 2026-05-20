# bore local

> Avvia un proxy locale verso un server remoto usando Bore.
> Maggiori informazioni: <https://github.com/ekzhang/bore#detailed-usage>.

- Espone una porta locale a un server Bore remoto:

`bore local {{[-t|--to]}} {{remote_server_address}} {{local_port}}`

- Espone un host locale specifico invece di `localhost`:

`bore local {{[-l|--local-host]}} {{host}} {{[-t|--to]}} {{remote_server_address}} {{local_port}}`

- Specifica esplicitamente una porta del server remoto:

`bore local {{[-t|--to]}} {{remote_server_address}} {{[-p|--port]}} {{remote_port}} {{local_port}}`

- Usa un segreto per l'autenticazione:

`bore local {{[-t|--to]}} {{remote_server_address}} {{[-s|--secret]}} {{your_secret}} {{local_port}}`

- Mostra aiuto:

`bore local {{[-h|--help]}}`
