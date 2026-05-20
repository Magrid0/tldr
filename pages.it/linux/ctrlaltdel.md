# ctrlaltdel

> Utilità per controllare cosa succede quando viene premuto CTRL+ALT+DEL.
> Maggiori informazioni: <https://manned.org/ctrlaltdel>.

- Ottiene l'impostazione corrente:

`ctrlaltdel`

- Imposta CTRL+ALT+DEL per riavviare immediatamente, senza alcuna preparazione:

`sudo ctrlaltdel hard`

- Imposta CTRL+ALT+DEL per riavviare "normalmente", dando ai processi la possibilità di uscire prima (invia SIGINT a PID1):

`sudo ctrlaltdel soft`
