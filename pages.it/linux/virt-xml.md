# virt-xml

> Modifica i file XML del dominio libvirt con opzioni esplicite da riga di comando.
> Nota: `domain` si riferisce al nome, UUID o ID delle VM esistenti.
> Vedi anche: `virsh`.
> Maggiori informazioni: <https://github.com/virt-manager/virt-manager/blob/main/man/virt-xml.rst>.

- Elenca tutte le sotto-opzioni per un'opzione specifica:

`virt-xml --{{opzione}}=?`

- Elenca tutte le sotto-opzioni per disco, rete e boot:

`virt-xml --disk=? --network=? --boot=?`

- Modifica un valore per un dominio specifico:

`virt-xml {{dominio}} --edit --{{opzione}} {{sotto_opzione}}={{nuovo_valore}}`

- Cambia la descrizione per un dominio specifico:

`virt-xml {{dominio}} --edit --metadata description="{{nuova_descrizione}}"`

- Abilita/Disabilita il menu del dispositivo di boot per un dominio specifico:

`virt-xml {{dominio}} --edit --boot bootmenu={{on|off}}`

- Collega un hub USB host a una VM in esecuzione (esegui `lsusb` per vedere un elenco di dispositivi USB con i loro ID):

`virt-xml {{dominio}} --update --add-device --hostdev {{bus}}.{{dispositivo}}`
