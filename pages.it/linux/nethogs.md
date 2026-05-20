# nethogs

> Monitora l'utilizzo della larghezza di banda per processo.
> Maggiori informazioni: <https://manned.org/nethogs>.

- Avvia NetHogs come root (dispositivo predefinito è `eth0`):

`sudo nethogs`

- Monitora la larghezza di banda su un dispositivo specifico:

`sudo nethogs {{dispositivo}}`

- Monitora la larghezza di banda su più dispositivi:

`sudo nethogs {{dispositivo1 dispositivo2 ...}}`

- Specifica la frequenza di aggiornamento:

`sudo nethogs -t {{secondi}}`
