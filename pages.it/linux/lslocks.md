# lslocks

> Elenca i bloccaggi del sistema locale.
> Maggiori informazioni: <https://manned.org/lslocks>.

- Elenca tutti i bloccaggi del sistema locale:

`lslocks`

- Elenca i bloccaggi con intestazioni di colonna definite:

`lslocks {{[-o|--output]}} {{PID,COMMAND,PATH,...}}`

- Elenca i bloccaggi producendo un output grezzo (senza colonne) e senza intestazioni di colonna:

`lslocks {{[-r|--raw]}} {{[-n|--noheadings]}}`

- Elenca i bloccaggi per PID in input:

`lslocks {{[-p|--pid]}} {{process_id}}`

- Elenca i bloccaggi con output JSON su `stdout`:

`lslocks {{[-J|--json]}}`
