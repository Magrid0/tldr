# xfce4-terminal

> L'emulatore di terminale XFCE4.
> Maggiori informazioni: <https://docs.xfce.org/apps/xfce4-terminal/start>.

- Apri una nuova finestra di terminale:

`xfce4-terminal`

- Imposta il titolo iniziale:

`xfce4-terminal --initial-title "{{titolo_iniziale}}"`

- Apri una nuova scheda nella finestra di terminale corrente:

`xfce4-terminal --tab`

- Esegui un comando in una nuova finestra di terminale:

`xfce4-terminal --command "{{comando_con_argomenti}}"`

- Tieni il terminale aperto dopo l'esecuzione del comando:

`xfce4-terminal --command "{{comando_con_argomenti}}" --hold`

- Apri più nuove schede, eseguendo un comando in ciascuna:

`xfce4-terminal --tab --command "{{comando1}}" --tab --command "{{comando2}}"`
