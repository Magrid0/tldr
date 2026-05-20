# systemctl preset

> Ripristina lo stato di abilitazione dei file di unità ai valori predefiniti specificati nei file delle politiche di preset.
> Vedi anche: `systemctl preset-all`, `systemctl list-unit-files`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#preset%20UNIT%E2%80%A6>.

- Ripristina lo stato di abilitazione ai predefiniti di preset:

`systemctl preset {{unità1 unità2 ...}}`

- Abilita solo se contrassegnato come abilitato nella politica di preset:

`systemctl preset {{unità}} --preset-mode enable-only`

- Disabilita solo se contrassegnato come disabilitato nella politica di preset:

`systemctl preset {{unità}} --preset-mode disable-only`

- Sopprime l'output e restituisce solo il codice di uscita:

`systemctl preset {{unità}} {{[-q|--quiet]}}`
