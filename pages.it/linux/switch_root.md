# switch_root

> Usa un filesystem differente come root dell'albero dei mount.
> Nota: `switch_root` fallirà se la nuova root non è la radice di un mount. Usa il bind-mounting come soluzione alternativa.
> Vedi anche: `chroot`, `mount`.
> Maggiori informazioni: <https://manned.org/switch_root>.

- Sposta `/proc`, `/dev`, `/sys` e `/run` nel filesystem specificato, usa questo filesystem come nuova root e avvia il processo init specificato:

`switch_root {{nuova_root}} {{/sbin/init}}`

- Mostra aiuto:

`switch_root {{[-h|--help]}}`
