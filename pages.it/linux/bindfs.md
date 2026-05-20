# bindfs

> Monta una directory altrove con permessi differenti.
> Maggiori informazioni: <https://bindfs.org/docs/bindfs.1.html>.

- Monta una directory con gli stessi permessi:

`sudo bindfs {{path/to/directory}} {{path/to/mount_point}}`

- Mappa oggetti del filesystem di proprietà di `user1` in modo che siano di proprietà di `user2` (si applica anche in reverse per i file appena creati):

`sudo bindfs --map={{user1}}/{{user2}} {{path/to/directory}} {{path/to/mount_point}}`

- Smonta una directory:

`sudo umount {{path/to/mount_point}}`
