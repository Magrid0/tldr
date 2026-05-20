# xdg-user-dirs-update

> Aggiorna le directory utente XDG.
> Vedi anche: `xdg-user-dir`.
> Maggiori informazioni: <https://manned.org/xdg-user-dirs-update>.

- Cambia la directory DESKTOP di XDG nella directory specificata:

`xdg-user-dirs-update --set DESKTOP "/{{path/to/directory}}"`

- Crea le directory mancanti:

`xdg-user-dirs-update --force`

- Scrivi il risultato nel file dry-run specificato invece del file `user-dirs.dirs`:

`xdg-user-dirs-update --dummy-output "{{path/to/file_dry_run}}" --set {{directory_utente_xdg}} "/{{path/to/directory}}"`
