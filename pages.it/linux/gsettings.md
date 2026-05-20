# gsettings

> Interroga e modifica le impostazioni dconf con validazione dello schema.
> Maggiori informazioni: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/using_the_desktop_environment_in_rhel_8/configuring-gnome-at-low-level_using-the-desktop-environment-in-rhel-8#using-gsettings-command_configuring-gnome-at-low-level>.

- Imposta il valore di una chiave. Fallisce se la chiave non esiste o il valore è fuori intervallo:

`gsettings set {{org.example.schema}} {{example-key}} {{value}}`

- Stampa il valore di una chiave o il predefinito fornito dallo schema se la chiave non è stata impostata in `dconf`:

`gsettings get {{org.example.schema}} {{example-key}}`

- Annulla l'impostazione di una chiave, così da usare il suo valore predefinito dello schema:

`gsettings reset {{org.example.schema}} {{example-key}}`

- Mostra tutti gli schemi (non rilocabili), chiavi e valori:

`gsettings list-recursively`

- Mostra tutte le chiavi e valori (predefinito se non impostato) da uno schema:

`gsettings list-recursively {{org.example.schema}}`

- Mostra i valori consentiti dallo schema per una chiave (utile con chiavi enum):

`gsettings range {{org.example.schema}} {{example-key}}`

- Mostra la descrizione leggibile di una chiave:

`gsettings describe {{org.example.schema}} {{example-key}}`
