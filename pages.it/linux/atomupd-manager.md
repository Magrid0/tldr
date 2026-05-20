# atomupd-manager

> Gestisce gli aggiornamenti di SteamOS.
> Maggiori informazioni: <https://github.com/evlaV/atomupd-daemon>.

- Controlla la presenza di aggiornamenti disponibili:

`sudo atomupd-manager check`

- Aggiorna a un'immagine specifica:

`sudo atomupd-manager update {{id_versione}}`

- Stampa il canale di aggiornamento attualmente tracciato:

`atomupd-manager tracked-branch`

- Elenca i canali di aggiornamento disponibili:

`atomupd-manager list-branches`

- Passa a un canale di aggiornamento specifico:

`sudo atomupd-manager switch-branch {{stable|beta|preview|rc|bc|pc|main}}`
