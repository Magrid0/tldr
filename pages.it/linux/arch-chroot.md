# arch-chroot

> Comando `chroot` migliorato per aiutare nel processo di installazione di Arch Linux.
> Maggiori informazioni: <https://manned.org/arch-chroot>.

- Avvia una shell interattiva (Bash, in modo predefinito) in una nuova directory root:

`arch-chroot {{path/to/nuova_root}}`

- Specifica l'utente (diverso dall'utente corrente) con cui eseguire la shell:

`arch-chroot -u {{utente}} {{path/to/nuova_root}}`

- Esegue un comando personalizzato (invece della Bash predefinita) nella nuova directory root:

`arch-chroot {{path/to/nuova_root}} {{comando}} {{argomenti_comando}}`

- Specifica la shell, diversa dalla Bash predefinita (in questo caso, il pacchetto `zsh` dovrebbe essere stato installato nel sistema di destinazione):

`arch-chroot {{path/to/nuova_root}} {{zsh}}`
