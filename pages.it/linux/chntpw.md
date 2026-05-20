# chntpw

> Un'utilità che può modificare il registro di Windows, reimpostare la password utente e promuovere utenti ad amministratore modificando il SAM di Windows.
> Avviare la macchina di destinazione con un live cd come Kali Linux ed eseguire con privilegi elevati.
> Maggiori informazioni: <https://pogostick.net/~pnh/ntpasswd/MANUAL.txt>.

- Elenca tutti gli utenti nel file SAM:

`chntpw -l {{path/to/sam_file}}`

- Modifica l'utente in modo interattivo:

`chntpw -u {{username}} {{path/to/sam_file}}`

- Utilizza chntpw in modo interattivo:

`chntpw -i {{path/to/sam_file}}`
