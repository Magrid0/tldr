# pacman --files

> Interroga il database locale dei file.
> Vedi anche: `pacman`, `pkgfile`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- Aggiorna il database dei pacchetti:

`sudo pacman -Fy`

- Trova il pacchetto che possiede un [F]ile specifico:

`pacman -F {{nome_file}}`

- Trova il pacchetto che possiede un [F]ile specifico, usando una `rege[x]`:

`pacman -Fx '{{regex}}'`

- Elenca solo i nomi dei pacchetti:

`pacman -Fq {{nome_file}}`

- [l]ista i [F]ile posseduti da un pacchetto specifico:

`pacman -Fl {{pacchetto}}`

- Mostra [h]elp:

`pacman -Fh`
