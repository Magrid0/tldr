# steamos-bootdebug

> Gestisce il processo di avvio di SteamOS.
> Maggiori informazioni: <https://gitlab.com/users/evlaV/projects>.

- Cambia ciò che SteamOS mostra all'avvio:

`sudo steamos-bootdebug {{kernel-debug|kernel-quiet|menu|verbose|quiet|status}}`

- Mostra il logging del kernel solo al prossimo avvio:

`sudo steamos-bootdebug {{kernel-debug-once}}`

- Imposta se il processo di avvio deve registrare in un file:

`sudo steamos-bootdebug log {{enable|disable}}`

- Mostra il file di log registrato:

`sudo steamos-bootdebug log show`
