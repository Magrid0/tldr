# qm disk

> Gestisce le immagini dei dischi.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_disk_import>.

- Aggiunge `n` gigabyte a un disco virtuale:

`qm {{[di|disk]}} {{[resi|resize]}} {{100}} {{disk_name}} +{{n}}G`

- Sposta un disco virtuale:

`qm {{[di|disk]}} {{[m|move]}} {{100}} {{destination}} {{index}}`

- Elimina la copia precedente del disco virtuale:

`qm {{[di|disk]}} {{[m|move]}} --delete {{100}} {{destination}} {{index}}`

- Importa un'immagine disco VMDK/`.qcow2`/raw usando un nome di storage specifico:

`qm {{[di|disk]}} {{[i|import]}} {{100}} {{path/to/disk}} {{storage_name}} --format {{qcow2|raw|vmdk}}`

- Riseleziona tutti gli storage e aggiorna le dimensioni dei dischi e le immagini disco inutilizzate:

`qm {{[di|disk]}} {{[resc|rescan]}}`

- Esegue una simulazione di riselezione senza scrivere modifiche alle configurazioni:

`qm {{[di|disk]}} {{[resc|rescan]}} --dryrun`

- Specifica una macchina virtuale tramite il suo ID:

`qm {{[di|disk]}} {{[resc|rescan]}} --vmid {{100}}`
