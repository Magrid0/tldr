# zenity

> Mostra dialoghi dalla riga di comando/script shell.
> Restituisce i valori inseriti dall'utente o 1 in caso di errore.
> Maggiori informazioni: <https://manned.org/zenity>.

- Mostra il dialogo di domanda predefinito:

`zenity --question`

- Mostra un dialogo informativo che mostra un messaggio:

`zenity --info --text "{{messaggio}}"`

- Mostra un modulo nome/password e restituisce i dati separati da ";" ("|" in modo predefinito):

`zenity --forms --add-entry "{{etichetta_nome}}" --add-password "{{etichetta_password}}" --separator ";"`

- Mostra un modulo di selezione file in cui l'utente può selezionare solo directory:

`zenity --file-selection --directory`

- Mostra una barra di progresso che aggiorna il suo messaggio ogni secondo e mostra una percentuale di progresso:

`{{(echo "#1"; sleep 1; echo "50"; echo "#2"; sleep 1; echo "100")}} | zenity --progress`
