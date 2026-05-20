# pacstrap

> Installa pacchetti di Arch Linux nella nuova directory root specificata.
> Maggiori informazioni: <https://manned.org/pacstrap>.

- Installa il pacchetto `base`, il kernel Linux e il firmware per hardware comune:

`pacstrap {{percorso/nuova_root}} {{base}} {{linux}} {{linux-firmware}}`

- Installa il pacchetto `base`, il kernel Linux LTS e gli strumenti di compilazione `base-devel`:

`pacstrap {{percorso/nuova_root}} {{base}} {{base-devel}} {{linux-lts}}`

- Installa pacchetti e copia la configurazione di Pacman dell'host nella destinazione:

`pacstrap -P {{percorso/nuova_root}} {{pacchetti}}`

- Installa pacchetti senza copiare la lista mirror dell'host nella destinazione:

`pacstrap -M {{percorso/nuova_root}} {{pacchetti}}`

- Usa un file di configurazione alternativo per Pacman:

`pacstrap -C {{percorso/pacman.conf}} {{percorso/nuova_root}} {{pacchetti}}`

- Installa pacchetti usando la cache dell'host invece che della destinazione:

`pacstrap -c {{percorso/nuova_root}} {{pacchetti}}`

- Inizializza un portachiavi `pacman` vuoto nella destinazione senza copiarlo dall'host:

`pacstrap -K {{percorso/nuova_root}} {{pacchetti}}`

- Installa pacchetti in modalità interattiva (richiede conferma):

`pacstrap -i {{percorso/nuova_root}} {{pacchetti}}`
