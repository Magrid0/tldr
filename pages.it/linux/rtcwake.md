# rtcwake

> Entra in uno stato di sospensione del sistema fino al momento di riattivazione specificato relativo all'orologio BIOS.
> Maggiori informazioni: <https://manned.org/rtcwake>.

- Mostra se un allarme è impostato o meno:

`sudo rtcwake {{[-m|--mode]}} show {{[-v|--verbose]}}`

- Sospende in RAM e si riattiva dopo 10 secondi:

`sudo rtcwake {{[-m|--mode]}} mem {{[-s|--seconds]}} {{10}}`

- Sospende su disco (maggiore risparmio energetico) e si riattiva 15 minuti dopo:

`sudo rtcwake {{[-m|--mode]}} disk --date +{{15}}min`

- Congela il sistema (più efficiente della sospensione in RAM ma richiede kernel Linux versione 3.9 o successiva) e si riattiva a una data e ora specificate:

`sudo rtcwake {{[-m|--mode]}} freeze --date {{YYYYMMDDhhmm}}`

- Disabilita un allarme impostato in precedenza:

`sudo rtcwake {{[-m|--mode]}} disable`

- Esegue una simulazione per riattivare il computer a un'ora specificata (premi `<Ctrl c>` per interrompere):

`sudo rtcwake {{[-m|--mode]}} on --date {{hh:ss}}`
