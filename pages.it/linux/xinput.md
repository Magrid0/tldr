# xinput

> Elenca i dispositivi di input disponibili, interroga informazioni su un dispositivo e modifica le impostazioni del dispositivo di input.
> Maggiori informazioni: <https://manned.org/xinput>.

- Elenca tutti i dispositivi di input:

`xinput list`

- Disabilita un input:

`xinput disable {{id}}`

- Abilita un input:

`xinput enable {{id}}`

- Disconnette un input dal suo master:

`xinput float {{id}}`

- Ricollega un input come slave a un master:

`xinput reattach {{id}} {{id_master}}`

- Elenca le impostazioni di un dispositivo di input:

`xinput list-props {{id}}`

- Modifica un'impostazione di un dispositivo di input:

`xinput set-prop {{id}} {{id_impostazione}} {{valore}}`
