# dialog

> Mostra finestre di dialogo sul terminale.
> Vedi anche: `gum`, `whiptail`.
> Maggiori informazioni: <https://manned.org/dialog>.

- Mostra un messaggio:

`dialog --msgbox "{{Message}}" {{height}} {{width}}`

- Chiede all'utente di inserire del testo:

`dialog --inputbox "{{Enter text:}}" {{8}} {{40}} 2>{{output.txt}}`

- Chiede all'utente una domanda sì/no:

`dialog --yesno "{{Continue?}}" {{7}} {{40}}`

- Mostra aiuto:

`dialog`
