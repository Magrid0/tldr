# kdialog

> Mostra finestre di dialogo KDE da script shell.
> Maggiori informazioni: <https://develop.kde.org/docs/administration/kdialog/>.

- Apre una finestra di dialogo che mostra un messaggio specifico:

`kdialog --msgbox "{{message}}" "{{optional_detailed_message}}"`

- Apre una finestra di dialogo con pulsanti `sì` e `no`, che restituiscono rispettivamente `0` e `1`:

`kdialog --yesno "{{message}}"`

- Apre una finestra di dialogo di avviso con pulsanti `sì`, `no` e `annulla`, che restituiscono rispettivamente `0`, `1` o `2`:

`kdialog --warningyesnocancel "{{message}}"`

- Apre una finestra di dialogo di input e stampa l'input su `stdout` quando si preme `OK`:

`kdialog --inputbox "{{message}}" "{{optional_default_text}}"`

- Apre una finestra di dialogo per richiedere una password specifica e la stampa su `stdout`:

`kdialog --password "{{message}}"`

- Apre una finestra di dialogo contenente un menu a tendina specifico e stampa l'elemento selezionato su `stdout`:

`kdialog --combobox "{{message}}" "{{item1}}" "{{item2}}" "{{...}}"`

- Apre una finestra di dialogo per la scelta di file e stampa il percorso del file selezionato su `stdout`:

`kdialog --getopenfilename`

- Apre una finestra di dialogo con barra di avanzamento e stampa un riferimento D-Bus per la comunicazione su `stdout`:

`kdialog --progressbar "{{message}}"`
