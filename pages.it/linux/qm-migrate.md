# qm migrate

> Migra una macchina virtuale.
> Usato per creare una nuova attività di migrazione.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_migrate>.

- Migra una macchina virtuale specifica:

`qm {{[mi|migrate]}} {{100}} {{target}}`

- Sostituisce il limite di larghezza di banda I/O corrente con 10 KiB/s:

`qm {{[mi|migrate]}} {{100}} {{target}} --bwlimit 10`

- Permette la migrazione di macchine virtuali che utilizzano dispositivi locali (solo root):

`qm {{[mi|migrate]}} {{100}} {{target}} --force true`

- Usa la migrazione online/live se una macchina virtuale è in esecuzione:

`qm {{[mi|migrate]}} {{100}} {{target}} --online true`

- Abilita la migrazione live dello storage per i dischi locali:

`qm {{[mi|migrate]}} {{100}} {{target}} --with-local-disks true`
