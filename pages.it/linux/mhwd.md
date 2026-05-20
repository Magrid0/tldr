# mhwd

> Utility di rilevamento hardware di Manjaro.
> Maggiori informazioni: <https://wiki.manjaro.org/index.php/Manjaro_Hardware_Detection_Overview>.

- Elenca i driver disponibili:

`mhwd {{[-l|--list]}}`

- Elenca i driver installati:

`mhwd {{[-li|--listinstalled]}}`

- Installa un driver:

`mhwd {{[-i|--install]}} {{pci|usb}} {{driver_name}}`

- Rimuove un driver:

`mhwd {{[-r|--remove]}} {{pci|usb}} {{driver_name}}`

- Mostra informazioni dettagliate sull'hardware rilevato:

`mhwd {{[-l|--list]}} {{[-d|--detail]}}`

- Installa automaticamente il miglior driver disponibile per la scheda grafica rilevata:

`mhwd {{[-a|--auto]}} pci {{free|nonfree}} 0300`
