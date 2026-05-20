# mount.steamos

> Monta o smonta partizioni del filesystem SteamOS.
> Maggiori informazioni: <https://gitlab.com/users/evlaV/projects>.

- Monta tutte le partizioni necessarie da un dispositivo a una directory di destinazione:

`sudo mount.steamos {{/dev/sdX}} {{/mnt}}`

- Monta con opzioni per escludere partizioni specifiche (es. `/home`, overlays):

`sudo mount.steamos {{[-o|--options]}} nohome,nooverlay {{/dev/sdX}} {{/mnt}}`

- Smonta tutte le partizioni montate sotto una directory di destinazione:

`sudo mount.steamos -u {{/mnt}}`

- Mostra aiuto:

`mount.steamos {{[-h|--help]}}`
