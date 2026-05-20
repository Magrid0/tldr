# vzdump

> Utility di backup per macchine virtuali e contenitori.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/vzdump.1.html>.

- Esegue il dump di una macchina virtuale guest nella directory di dump predefinita (di solito `/var/lib/vz/dump/`), escludendo gli snapshot:

`vzdump {{id_vm}}`

- Esegue il backup delle macchine virtuali guest con gli ID 101, 102 e 103:

`vzdump {{101 102 103}}`

- Esegue il dump di una macchina virtuale guest usando una modalità specifica:

`vzdump {{id_vm}} --mode {{suspend|snapshot}}`

- Esegue il backup di tutti i sistemi guest e invia una notifica email agli utenti root e admin:

`vzdump --all --mode {{suspend}} --mailto {{root}} --mailto {{admin}}`

- Usa la modalità snapshot (nessun downtime richiesto) e una directory di dump non predefinita:

`vzdump {{id_vm}} --dumpdir {{percorso/della/directory}} --mode {{snapshot}}`

- Esegue il backup di tutte le macchine virtuali guest escludendo gli ID 101 e 102:

`vzdump --mode {{suspend}} --exclude {{101, 102}}`
