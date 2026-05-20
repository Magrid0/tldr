# chcat

> Modifica la categoria di sicurezza SELinux per i file.
> Le categorie forniscono un livello aggiuntivo di controllo degli accessi basato su MCS (Multi-Category Security).
> Vedi anche: `chcon`, `semanage`.
> Maggiori informazioni: <https://manned.org/chcat>.

- Elenca tutte le categorie disponibili:

`sudo chcat {{[-L|--list]}}`

- Aggiunge una categoria a un file:

`sudo chcat +{{CategoryName}} {{path/to/file}}`

- Rimuove una categoria da un file:

`sudo chcat -- -{{CategoryName}} {{path/to/file}}`

- Imposta categorie specifiche per un file (sostituendo quelle esistenti):

`sudo chcat {{CategoryName1,CategoryName2,...}} {{path/to/file}}`

- Mostra le categorie di un file:

`ls {{[-Z|--context]}} {{path/to/file}}`

- Rimuove tutte le categorie da un file:

`sudo chcat {{[-d|--delete]}} {{path/to/file}}`
