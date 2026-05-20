# htpdate

> Sincronizza data e ora locali tramite intestazioni HTTP da server web.
> Maggiori informazioni: <https://www.vervest.org/htp/>.

- Sincronizza data e ora:

`sudo htpdate {{host}}`

- Esegue una simulazione di sincronizzazione, senza alcuna azione:

`htpdate -q {{host}}`

- Compensa la deriva sistematica dell'orologio:

`sudo htpdate -x {{host}}`

- Imposta l'ora immediatamente dopo la sincronizzazione:

`sudo htpdate -s {{host}}`
