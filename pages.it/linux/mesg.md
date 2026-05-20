# mesg

> Controlla o imposta la capacità di un terminale di ricevere messaggi da altri utenti, solitamente dal comando `write`.
> Vedi anche: `write`, `talk`.
> Maggiori informazioni: <https://manned.org/mesg>.

- Controlla se il terminale è aperto alla scrittura di messaggi:

`mesg`

- Impedisce la ricezione di messaggi da altri utenti:

`mesg n`

- Permette la ricezione di messaggi da altri utenti:

`mesg y`

- Abilita la modalità verbosa, mostrando un avviso se il comando non viene eseguito da un terminale:

`mesg {{[-v|--verbose]}}`
