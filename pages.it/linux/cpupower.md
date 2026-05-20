# cpupower

> Strumenti per le opzioni di CPU e risparmio energetico.
> Maggiori informazioni: <https://manned.org/cpupower>.

- Elenca le CPU:

`sudo cpupower {{[-c|--cpu]}} {{all}} info`

- Stampa informazioni su tutti i core:

`sudo cpupower {{[-c|--cpu]}} {{all}} info`

- Imposta tutte le CPU su un governor di frequenza per il risparmio energetico:

`sudo cpupower {{[-c|--cpu]}} {{all}} frequency-set --governor {{powersave}}`

- Stampa i governor di frequenza disponibili per la CPU 0:

`sudo cpupower {{[-c|--cpu]}} {{0}} frequency-info {{[-g|--governors]}} | grep "analyzing\|governors"`

- Stampa la frequenza della CPU 4 dall'hardware, in un formato leggibile:

`sudo cpupower {{[-c|--cpu]}} {{4}} frequency-info {{[-w|--hwfreq]}} {{[-m|--human]}}`
