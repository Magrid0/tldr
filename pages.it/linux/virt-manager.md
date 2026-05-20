# virt-manager

> Un'interfaccia utente desktop per gestire macchine virtuali KVM e Xen e contenitori LXC.
> Maggiori informazioni: <https://manned.org/virt-manager>.

- Avvia la GUI:

`virt-manager`

- Connettiti a un hypervisor:

`virt-manager --connect {{uri_hypervisor}}`

- Non mettere in background il processo virt-manager all'avvio:

`virt-manager --no-fork`

- Stampa output di debug:

`virt-manager --debug`

- Apri la procedura guidata "Nuova VM":

`virt-manager --show-domain-creator`

- Mostra la finestra dei dettagli del dominio per una macchina virtuale/contenitore specifico:

`virt-manager --show-domain-editor {{nome|id|uuid}}`

- Mostra la finestra delle prestazioni del dominio per una macchina virtuale/contenitore specifico:

`virt-manager --show-domain-performance {{nome|id|uuid}}`

- Mostra la finestra dei dettagli di connessione:

`virt-manager --show-host-summary`
