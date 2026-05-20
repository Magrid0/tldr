# chfn

> Aggiorna le informazioni `finger` per un utente.
> Maggiori informazioni: <https://manned.org/chfn>.

- Aggiorna il campo "Name" di un utente nell'output di `finger`:

`chfn {{[-f|--full-name]}} {{new_display_name}} {{username}}`

- Aggiorna il campo "Office Room Number" di un utente per l'output di `finger`:

`chfn {{[-o|--office]}} {{new_office_room_number}} {{username}}`

- Aggiorna il campo "Office Phone Number" di un utente per l'output di `finger`:

`chfn {{[-p|--office-phone]}} {{new_office_telephone_number}} {{username}}`

- Aggiorna il campo "Home Phone Number" di un utente per l'output di `finger`:

`chfn {{[-h|--home-phone]}} {{new_home_telephone_number}} {{username}}`
