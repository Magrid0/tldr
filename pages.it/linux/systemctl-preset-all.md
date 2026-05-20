# systemctl preset-all

> Ripristina lo stato di abilitazione di tutte le unità installate ai valori predefiniti specificati nei file delle politiche di preset.
> Vedi anche: `systemctl preset`, `systemctl list-unit-files`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#preset-all>.

- Ripristina lo stato di abilitazione di tutte le unità installate:

`sudo systemctl preset-all`

- Abilita solo se contrassegnato come abilitato nella politica di preset:

`sudo systemctl preset-all --preset-mode enable-only`

- Disabilita solo se contrassegnato come disabilitato nella politica di preset:

`sudo systemctl preset-all --preset-mode disable-only`

- Sopprime l'output e restituisce solo il codice di uscita:

`sudo systemctl preset-all {{[-q|--quiet]}}`
