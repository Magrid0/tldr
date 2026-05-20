# konsave

> Salva e applica le personalizzazioni di Linux con un solo comando.
> Maggiori informazioni: <https://github.com/Prayag2/konsave>.

- Salva la configurazione corrente come profilo:

`konsave {{[-s|--save]}} {{profile_name}}`

- Applica un profilo:

`konsave {{[-a|--apply]}} {{profile_name}}`

- Salva la configurazione corrente come profilo, sovrascrivendo i profili esistenti se hanno lo stesso nome:

`konsave {{[-s|--save]}} {{profile_name}} {{[-f|--force]}}`

- Elenca tutti i profili:

`konsave {{[-l|--list]}}`

- Rimuove un profilo:

`konsave {{[-r|--remove]}} {{profile_name}}`

- Esporta un profilo come `.knsv` nella home directory:

`konsave {{[-e|--export-profile]}} {{profile_name}}`

- Importa un profilo `.knsv`:

`konsave {{[-i|--import-profile]}} {{path/to/profile_name.knsv}}`
