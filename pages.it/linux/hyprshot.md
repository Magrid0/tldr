# hyprshot

> Utility per screenshot per il compositore Wayland Hyprland.
> Maggiori informazioni: <https://github.com/Gustash/Hyprshot>.

- Seleziona e cattura uno screenshot di una regione:

`hyprshot {{[-m|--mode]}} region`

- Seleziona e cattura uno screenshot di una finestra specifica:

`hyprshot {{[-m|--mode]}} window`

- Seleziona e cattura uno screenshot di un'uscita specifica:

`hyprshot {{[-m|--mode]}} output`

- Cattura uno screenshot della finestra attualmente attiva:

`hyprshot {{[-m|--mode]}} active {{[-m|--mode]}} window`

- Congela lo schermo e cattura uno screenshot della regione selezionata:

`hyprshot {{[-z|--freeze]}} {{[-m|--mode]}} region`

- Seleziona e cattura uno screenshot di una finestra specifica, salvando nella directory di output indicata:

`hyprshot {{[-o|--output-folder]}} {{path/to/directory}} {{[-m|--mode]}} window`

- Seleziona e cattura uno screenshot di un'uscita specifica, salvando lo screenshot solo negli appunti:

`hyprshot --clipboard {{[-m|--mode]}} output`
