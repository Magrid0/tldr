# iwlist

> Ottiene informazioni dettagliate da un'interfaccia wireless.
> Maggiori informazioni: <https://manned.org/iwlist>.

- Mostra l'elenco dei punti di accesso e delle celle ad-hoc nel raggio d'azione:

`iwlist {{wireless_interface}} scan`

- Mostra le frequenze disponibili nel dispositivo:

`iwlist {{wireless_interface}} frequency`

- Elenca le velocità di trasmissione supportate dal dispositivo:

`iwlist {{wireless_interface}} rate`

- Elenca i parametri di autenticazione WPA attualmente impostati:

`iwlist {{wireless_interface}} auth`

- Elenca tutte le chiavi di crittografia WPA impostate nel dispositivo:

`iwlist {{wireless_interface}} wpakeys`

- Elenca le dimensioni delle chiavi di crittografia supportate e tutte le chiavi di crittografia impostate nel dispositivo:

`iwlist {{wireless_interface}} keys`

- Elenca i vari attributi e modalità di gestione dell'alimentazione del dispositivo:

`iwlist {{wireless_interface}} power`

- Elenca gli elementi informativi generici impostati nel dispositivo (usati per il supporto WPA):

`iwlist {{wireless_interface}} genie`
