# selinuxenabled

> Verifica se SELinux è abilitato.
> Restituisce codice di uscita 0 se SELinux è abilitato, e 1 se non lo è.
> Vedi anche: `getenforce`, `setenforce`, `sestatus`.
> Maggiori informazioni: <https://manned.org/selinuxenabled>.

- Verifica se SELinux è abilitato (nessun output; verifica il codice di uscita con `echo $?`):

`selinuxenabled`

- Verifica se SELinux è abilitato e stampa il risultato:

`selinuxenabled && echo "SELinux is enabled" || echo "SELinux is disabled"`

- Usa in uno script shell per eseguire comandi in modo condizionale:

`if selinuxenabled; then echo "SELinux is running"; fi`
