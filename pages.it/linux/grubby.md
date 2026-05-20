# grubby

> Strumento per configurare i bootloader `grub` e `zipl`.
> Maggiori informazioni: <https://manned.org/grubby.8>.

- Aggiunge argomenti di avvio del kernel a tutte le voci del menu del kernel:

`sudo grubby --update-kernel=ALL --args '{{quiet console=ttyS0}}'`

- Rimuove argomenti esistenti dalla voce per il kernel predefinito:

`sudo grubby --update-kernel=DEFAULT --remove-args {{quiet}}`

- Elenca tutte le voci del menu del kernel:

`sudo grubby --info=ALL`
