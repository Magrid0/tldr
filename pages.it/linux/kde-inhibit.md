# kde-inhibit

> Inibisce varie funzioni del desktop mentre un comando è in esecuzione.
> Maggiori informazioni: <https://invent.kde.org/plasma/kde-cli-tools/-/blob/master/kdeinhibit/main.cpp>.

- Inibisce la gestione dell'alimentazione:

`kde-inhibit --power {{command}} {{command_arguments}}`

- Inibisce il salvaschermo:

`kde-inhibit --screenSaver {{command}} {{command_arguments}}`

- Avvia VLC e inibisce la correzione del colore (modalità notte) mentre è in esecuzione:

`kde-inhibit --colorCorrect {{vlc}}`
