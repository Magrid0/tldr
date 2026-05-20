# runlim

> Campiona e limita il tempo e l'uso della memoria di un programma e dei suoi processi figli usando il filesystem proc su Linux.
> Maggiori informazioni: <https://fmv.jku.at/runlim/>.

- Stampa il tempo e l'uso della memoria di un comando:

`runlim {{command}} {{command_arguments}}`

- Registra le statistiche in un file invece di `stdout`:

`runlim --output-file={{path/to/file}} {{command}} {{command_arguments}}`

- Limita il tempo a un limite superiore (in secondi):

`runlim --time-limit={{number}} {{command}} {{command_arguments}}`

- Limita il tempo reale a un limite superiore (in secondi):

`runlim --real-time-limit={{number}} {{command}} {{command_arguments}}`

- Limita lo spazio a un limite superiore (in MB):

`runlim --space-limit={{number}} {{command}} {{command_arguments}}`
