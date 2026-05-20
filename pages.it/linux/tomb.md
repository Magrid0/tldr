# tomb

> Gestisci directory di archiviazione crittografate che possono essere trasportate e nascoste in modo sicuro in un filesystem.
> Maggiori informazioni: <https://dyne.org/docs/tomb/manpage/>.

- Crea una nuova tomba con una dimensione iniziale di 100 MB:

`tomb dig -s {{100}} {{directory_crittografata.tomb}}`

- Crea un nuovo file chiave che può essere usato per bloccare una tomba; verrà richiesta una password per la chiave:

`tomb forge {{directory_crittografata.tomb.key}}`

- Forza la creazione di una nuova chiave, anche se la tomba non consente la forgiatura (a causa dello swap):

`tomb forge {{directory_crittografata.tomb.key}} -f`

- Inizializza e blocca una tomba vuota usando una chiave creata con `forge`:

`tomb lock {{directory_crittografata.tomb}} -k {{directory_crittografata.tomb.key}}`

- Monta una tomba (di default in `/media`) usando la sua chiave, rendendola utilizzabile come una normale directory del filesystem:

`tomb open {{directory_crittografata.tomb}} -k {{directory_crittografata.tomb.key}}`

- Chiudi una tomba (fallisce se la tomba è in uso da un processo):

`tomb close {{directory_crittografata.tomb}}`

- Forza la chiusura di tutte le tombe aperte, terminando qualsiasi applicazione che le utilizza:

`tomb slam all`

- Elenca tutte le tombe aperte:

`tomb list`
