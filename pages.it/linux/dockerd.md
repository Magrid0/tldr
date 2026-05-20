# dockerd

> Un processo persistente per avviare e gestire container Docker.
> Maggiori informazioni: <https://docs.docker.com/reference/cli/dockerd/>.

- Esegue il demone Docker:

`dockerd`

- Esegue il demone Docker e lo configura per ascoltare su socket specifici (UNIX e TCP):

`dockerd {{[-H|--host]}} unix://{{path/to/tmp.sock}} {{[-H|--host]}} tcp://{{ip_address}}`

- Esegue con un file PID del demone specifico:

`dockerd {{[-p|--pidfile]}} {{path/to/pid_file}}`

- Esegue in modalità debug:

`dockerd {{[-D|--debug]}}`

- Esegue e imposta un livello di log specifico:

`dockerd {{[-l|--log-level]}} {{debug|info|warn|error|fatal}}`
