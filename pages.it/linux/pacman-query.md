# pacman --query

> Interroga il database locale dei pacchetti.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- [Q]uery il database locale dei pacchetti e mostra i pacchetti installati e le versioni:

`pacman -Q`

- Mostra solo i pacchetti installati [e]splicitamente senza numeri di versione:

`pacman -Qeq`

- Trova il pacchetto che [p]ossiede un file:

`pacman -Qo {{nome_file}}`

- Mostra informazioni su un pacchetto [i]nstallato:

`pacman -Qi {{pacchetto}}`

- Mostra l'[e]lenco dei file posseduti da un pacchetto specifico:

`pacman -Ql {{pacchetto}}`

- Mostra i pacchetti orfani (installati come [d]ipendenze ma attualmente non richiesti ([t]) da nessun pacchetto) in modalità [q]uieta (viene mostrato solo il nome del pacchetto):

`pacman -Qdtq`

- Mostra i pacchetti installati estranei ([m]) al database del repository:

`pacman -Qm`

- Mostra i pacchetti che possono essere [a]ggiornati:

`pacman -Qu`
