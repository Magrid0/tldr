# lynis

> Strumento di auditing di sistema e sicurezza.
> Maggiori informazioni: <https://cisofy.com/documentation/lynis/>.

- Controlla che Lynis sia aggiornato:

`sudo lynis update info`

- Esegue un audit di sicurezza del sistema:

`sudo lynis audit system`

- Esegue un audit di sicurezza di un Dockerfile:

`sudo lynis audit dockerfile {{path/to/dockerfile}}`
