# rpmconf

> Gestisce i file `.rpmnew`, `.rpmsave` e `.rpmorig` lasciati dagli aggiornamenti dei pacchetti.
> Vedi anche: `rpm`.
> Maggiori informazioni: <https://manned.org/rpmconf.8>.

- Elenca i file rimasti e sceglie interattivamente cosa fare con ciascuno di essi:

`sudo rpmconf {{[-a|--all]}}`

- Elimina i file `.rpmnew` e `.rpmsave` orfani:

`sudo rpmconf {{[-a|--all]}} {{[-c|--clean]}}`
