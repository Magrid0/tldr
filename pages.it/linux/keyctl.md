# keyctl

> Manipola il keyring del kernel Linux.
> Maggiori informazioni: <https://manned.org/keyctl>.

- Elenca le chiavi in un keyring specifico:

`keyctl list {{target_keyring}}`

- Elenca le chiavi correnti nella sessione predefinita dell'utente:

`keyctl list {{@us}}`

- Memorizza una chiave in un keyring specifico:

`keyctl add {{type_keyring}} {{key_name}} {{key_value}} {{target_keyring}}`

- Memorizza una chiave con il suo valore da `stdin`:

`echo -n {{key_value}} | keyctl padd {{type_keyring}} {{key_name}} {{target_keyring}}`

- Imposta un timeout su una chiave:

`keyctl timeout {{key_name}} {{timeout_in_seconds}}`

- Legge una chiave e la formatta come dump esadecimale se non stampabile:

`keyctl read {{key_name}}`

- Legge una chiave e la formatta così com'è:

`keyctl pipe {{key_name}}`

- Revoca una chiave e impedisce qualsiasi ulteriore azione su di essa:

`keyctl revoke {{key_name}}`
