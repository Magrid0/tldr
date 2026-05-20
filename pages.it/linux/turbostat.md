# turbostat

> Mostra statistiche di topologia del processore, frequenza, temperatura, potenza e idle.
> Maggiori informazioni: <https://manned.org/turbostat>.

- Mostra statistiche ogni 5 secondi:

`sudo turbostat`

- Mostra statistiche ogni numero specificato di secondi:

`sudo turbostat {{[-i|--interval]}} {{n_secondi}}`

- Non decodificare e stampare le informazioni di intestazione della configurazione di sistema:

`sudo turbostat --quiet`

- Mostra informazioni utili sulla CPU ogni 1 secondo, senza informazioni di intestazione:

`sudo turbostat --quiet {{[-i|--interval]}} 1 --cpu 0-{{numero_thread_cpu}} --show "PkgWatt","Busy%","Core","CoreTmp","Thermal"`

- Mostra aiuto:

`turbostat --help`
