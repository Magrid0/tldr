# restorecond

> Demonio che monitora la creazione di file e ripristina automaticamente i contesti SELinux.
> Utile per directory dove i file vengono creati frequentemente con contesti errati.
> Vedi anche: `restorecon`, `semanage-fcontext`.
> Maggiori informazioni: <https://manned.org/restorecond>.

- Avvia il demone `restorecond`:

`sudo restorecond`

- Esegue `restorecond` in modalità [v]erbosa per vedere gli eventi di ripristino:

`sudo restorecond -v`

- Esegue `restorecond` in modalità [d]ebug:

`sudo restorecond -d`

- Usa un file `restorecond.conf` alternativo:

`sudo restorecond -f restorecond_file`

- Controlla lo stato del servizio restorecond:

`sudo systemctl status restorecond`

- Abilita restorecond all'avvio:

`sudo systemctl enable restorecond --now`
