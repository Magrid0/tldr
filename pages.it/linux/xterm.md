# xterm

> Un emulatore di terminale per X Window System.
> Maggiori informazioni: <https://manned.org/xterm>.

- Apri il terminale con un titolo di `Example`:

`xterm -T {{Example}}`

- Apri il terminale in modalità schermo intero:

`xterm -fullscreen`

- Apri il terminale con sfondo blu scuro e primo piano giallo (colore del carattere):

`xterm -bg {{darkblue}} -fg {{yellow}}`

- Apri il terminale con 100 caratteri per riga e 35 righe, in posizione schermo x=200px, y=20px:

`xterm -geometry {{100}}x{{35}}+{{200}}+{{20}}`

- Apri il terminale usando un carattere Serif e una dimensione del carattere pari a 20:

`xterm -fa '{{Serif}}' -fs {{20}}`
