# virt-sysprep

> Reimposta, riconfigura o personalizza un'immagine di macchina virtuale.
> Questo comando può essere usato su una macchina virtuale o direttamente su un'immagine del disco della macchina virtuale.
> Nota: Potrebbe essere necessario passare `--connect URI` ai comandi o configurare l'URI in `$XDG_CONFIG_HOME/libvirt/libvirt.conf`.
> Maggiori informazioni: <https://libguestfs.org/virt-sysprep.1.html>.

- Elenca tutte le operazioni supportate (le operazioni abilitate per impostazione predefinita sono indicate con asterischi):

`virt-sysprep --list-operations`

- Esegue solo le operazioni specificate:

`sudo virt-sysprep {{[-d|--domain]}} {{nome_vm}} --operations {{operazione1,operazione2,...}}`

- Rimuove i dati sensibili del sistema da un'immagine di macchina virtuale (operazioni marcate come predefinite):

`sudo virt-sysprep {{[-a|--add]}} {{percorso/dell/immagine.qcow2}}`

- Specifica una macchina virtuale tramite nome ed esegue tutte le operazioni abilitate ma senza applicare effettivamente le modifiche:

`sudo virt-sysprep {{[-d|--domain]}} {{nome_vm}} {{[-n|--dry-run]}}`

- Reimposta le configurazioni di rete di NetworkManager, i mapping MAC persistenti e l'hostname per evitare conflitti di rete:

`sudo virt-sysprep {{[-d|--domain]}} {{nome_vm}} --operations machine-id,net-hwaddr,net-hostname,net-nmconn,customize --hostname {{nuovo_hostname}}`

- Imposta la password di root per un'immagine del disco:

`sudo virt-sysprep {{[-a|--add]}} {{percorso/dell/immagine.qcow2}} --operations customize --root-password password:{{nuova_password}}`

- Inietta un nuovo utente con una password definita e lo aggiunge al gruppo sudo:

`sudo virt-sysprep {{[-a|--add]}} {{percorso/dell/immagine.qcow2}} --run-command 'useradd -m {{nome_utente}} && echo {{nome_utente}}:{{password}} | chpasswd && usermod -aG sudo {{nome_utente}}'`

- Installa pacchetti specifici su un'immagine del disco (usa `--update` per aggiornare tutti i pacchetti installati all'ultima versione):

`sudo virt-sysprep {{[-a|--add]}} {{percorso/dell/immagine.qcow2}} --operations customize --network --install {{nome_pacchetto1,nome_pacchetto2,...}}`
