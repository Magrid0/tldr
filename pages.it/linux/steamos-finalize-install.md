# steamos-finalize-install

> Completa un'installazione di SteamOS configurando i bootloader e applicando gli aggiornamenti di sistema.
> Maggiori informazioni: <https://gitlab.com/users/evlaV/projects>.

- Finalizza l'installazione:

`sudo steamos-finalize-install`

- Finalizza senza aggiornare bootloader o kernel:

`sudo steamos-finalize-install --no-bootloaders --no-kernel`

- Salta tutti i passaggi di migrazione:

`sudo steamos-finalize-install --no-migrate`

- Imposta un root hash specifico durante la finalizzazione:

`sudo steamos-finalize-install --roothash {{hash}}`

- Forza i passaggi di migrazione del sistema indipendentemente dall'ambiente:

`sudo steamos-finalize-install --force`
