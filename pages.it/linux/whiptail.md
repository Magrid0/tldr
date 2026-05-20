# whiptail

> Mostra finestre di dialogo basate su testo dagli script shell.
> Vedi anche: `dialog`, `gum`.
> Maggiori informazioni: <https://manned.org/whiptail>.

- Mostra un messaggio semplice:

`whiptail --title "{{titolo}}" --msgbox "{{messaggio}}" {{altezza}} {{larghezza}}`

- Mostra una scelta booleana, restituendo il risultato tramite codice di uscita:

`whiptail --title "{{titolo}}" --yesno "{{messaggio}}" {{altezza}} {{larghezza}}`

- Personalizza il testo sui pulsanti sì/no:

`whiptail --title "{{titolo}}" --yes-button "{{testo}}" --no-button "{{testo}}" --yesno "{{messaggio}}" {{altezza}} {{larghezza}}`

- Mostra una casella di input di testo:

`{{risultato}}="$(whiptail --title "{{titolo}}" --inputbox "{{messaggio}}" {{altezza}} {{larghezza}} {{testo_predefinito}} 3>&1 1>&2 2>&3)"`

- Mostra una casella di input per password:

`{{risultato}}="$(whiptail --title "{{titolo}}" --passwordbox "{{messaggio}}" {{altezza}} {{larghezza}} 3>&1 1>&2 2>&3)"`

- Mostra un menu a scelta multipla:

`{{risultato}}=$(whiptail --title "{{titolo}}" --menu "{{messaggio}}" {{altezza}} {{larghezza}} {{altezza_menu}} {{"valore_1" "testo_visualizzato_1" "valore_2" "testo_visualizzato_2" ...}} 3>&1 1>&2 2>&3)`
