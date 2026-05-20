# update-rc.d

> Installa e rimuove servizi che sono collegamenti a script init in stile System-V.
> Gli script init si trovano in `/etc/init.d/`.
> Maggiori informazioni: <https://manned.org/update-rc.d>.

- Installa un servizio:

`update-rc.d {{mysql}} defaults`

- Abilita un servizio:

`update-rc.d {{mysql}} enable`

- Disabilita un servizio:

`update-rc.d {{mysql}} disable`

- Rimuovi forzatamente un servizio:

`update-rc.d -f {{mysql}} remove`
