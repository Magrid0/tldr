# mount.cifs

> Monta condivisioni SMB (Server Message Block) o CIFS (Common Internet File System).
> Nota: puoi anche fare la stessa cosa passando l'opzione `-t cifs` a `mount`.
> Maggiori informazioni: <https://manned.org/mount.cifs>.

- Collegati usando il nome utente specificato o `$USER` per impostazione predefinita (ti verrà richiesta una password):

`mount.cifs -o user={{username}} //{{server}}/{{share_name}} {{mountpoint}}`

- Collegati come utente ospite (senza password):

`mount.cifs -o guest //{{server}}/{{share_name}} {{mountpoint}}`

- Imposta le informazioni di proprietà per la directory montata:

`mount.cifs -o uid={{user_id|username}},gid={{group_id|groupname}} //{{server}}/{{share_name}} {{mountpoint}}`
