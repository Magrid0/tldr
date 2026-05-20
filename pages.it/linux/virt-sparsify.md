# virt-sparsify

> Rende le immagini dei drive delle macchine virtuali thin-provisioned.
> Nota: Usa solo per macchine offline per evitare la corruzione dei dati.
> Maggiori informazioni: <https://manned.org/virt-sparsify>.

- Crea un'immagine compressa sparsificata senza snapshot da una non sparsificata:

`virt-sparsify --compress {{percorso/dell/immagine.qcow2}} {{percorso/della/nuova_immagine.qcow2}}`

- Sparsifica un'immagine in-place:

`virt-sparsify --in-place {{percorso/dell/immagine.img}}`

- Converti da un formato immagine a un altro:

`virt-sparsify {{percorso/dell/immagine}} --convert {{qcow2|raw|vdi|...}} {{percorso/della/nuova_immagine}}`
