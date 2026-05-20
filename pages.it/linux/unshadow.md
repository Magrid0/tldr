# unshadow

> Utility fornita dal progetto John the Ripper per ottenere il file password Unix tradizionale se il sistema usa password shadow.
> Maggiori informazioni: <https://www.openwall.com/john/doc/>.

- Combina i file `/etc/shadow` e `/etc/passwd` del sistema corrente:

`sudo unshadow /etc/passwd /etc/shadow`

- Combina due file shadow e password arbitrari:

`sudo unshadow {{percorso/del/passwd}} {{percorso/dello/shadow}}`
