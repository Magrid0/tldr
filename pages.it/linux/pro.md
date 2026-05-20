# pro

> Gestisce i servizi Ubuntu Pro.
> Maggiori informazioni: <https://manned.org/ubuntu-advantage>.

- Collega il tuo sistema al contratto di supporto Ubuntu Pro:

`sudo pro attach`

- Mostra lo stato dei servizi Ubuntu Pro:

`pro status`

- Controlla se il sistema è affetto da una vulnerabilità specifica (e applica una correzione se possibile):

`pro fix {{numero-CVE}}`

- Mostra il numero di pacchetti non supportati:

`pro security-status`

- Elenca i pacchetti che non sono più disponibili per il download:

`pro security-status --unavailable`

- Elenca i pacchetti di terze parti:

`pro security-status --thirdparty`
