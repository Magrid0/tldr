# rauc

> Client di aggiornamento leggero per dispositivi Linux embedded per creare, ispezionare e installare bundle di aggiornamento.
> Maggiori informazioni: <https://manned.org/rauc>.

- Mostra lo stato corrente del sistema e la panoramica delle partizioni:

`rauc status`

- Installa un bundle di aggiornamento:

`rauc install {{path/to/bundle.raucb|https://example.com/bundle.raucb}}`

- Mostra informazioni su un bundle di aggiornamento specifico:

`rauc info {{path/to/bundle.raucb}}`

- Crea un bundle di aggiornamento firmato da una directory:

`rauc bundle --cert {{path/to/cert.pem}} --key {{path/to/key.pem}} {{path/to/input_dir}} {{path/to/output.raucb}}`

- Estrae il contenuto di un bundle di aggiornamento:

`rauc extract {{path/to/bundle.raucb}} {{path/to/output_directory}}`

- Marca la partizione attualmente avviata come buona per confermare l'aggiornamento riuscito:

`rauc status mark-good`

- Marca una partizione specifica come danneggiata per impedirne l'avvio:

`rauc status mark-bad {{slot_name}}`

- Cambia la partizione di avvio attiva con l'altra partizione disponibile:

`rauc status mark-active other`
