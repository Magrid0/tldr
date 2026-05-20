# pkexec

> Esegue comandi come un altro utente.
> Chiede la password in una GUI se disponibile.
> Vedi anche: `sudo`, `run0`, `doas`.
> Maggiori informazioni: <https://polkit.pages.freedesktop.org/polkit/pkexec.1.html>.

- Esegue un comando come root:

`pkexec {{comando}}`

- Cambia utente a root:

`pkexec`

- Esegue un comando come utente specifico:

`pkexec --user {{nome_utente}} {{comando}}`
