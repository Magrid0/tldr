# whiptail

> Mostra finestre di dialogo basate su testo dagli script shell.
> Vedi anche: `dialog`, `gum`.
> Maggiori informazioni: <https://manned.org/whiptail>.

- Mostra un messaggio semplice:

`whiptail --title "{{titolo}}" --msgbox "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}}`

- Mostra una scelta booleana, restituendo il risultato tramite codice di uscita:

`whiptail --title "{{titolo}}" --yesno "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}}`

- Personalizza il testo sui pulsanti sì/no:

`whiptail --title "{{titolo}}" --yes-button "{{testo}}" --no-button "{{testo}}" --yesno "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}}`

- Mostra una casella di input di testo:

`{{nome_variabile_risultato}}="$(whiptail --title "{{titolo}}" --inputbox "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}} {{testo_predefinito}} 3>&1 1>&2 2>&3)"`

- Mostra una casella di input per password:

`{{nome_variabile_risultato}}="$(whiptail --title "{{titolo}}" --passwordbox "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}} 3>&1 1>&2 2>&3)"`

- Mostra un menu a scelta multipla:

`{{nome_variabile_risultato}}=$(whiptail --title "{{titolo}}" --menu "{{messaggio}}" {{altezza_in_caratteri}} {{larghezza_in_caratteri}} {{altezza_visualizzazione_menu}} {{"valore_1" "testo_visualizzato_1" "valore_2" "testo_visualizzato_2" ...}} 3>&1 1>&2 2>&3)`
