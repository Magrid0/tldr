# protontricks

> Un semplice wrapper che esegue comandi Winetricks per giochi abilitati a Proton.
> Maggiori informazioni: <https://github.com/Matoking/protontricks#usage>.

- Esegue l'interfaccia grafica di protontricks:

`protontricks --gui`

- Esegue Winetricks per un gioco specifico:

`protontricks {{appid}} {{argomenti_winetricks}}`

- Esegue un comando nella directory di installazione di un gioco:

`protontricks {{[-c|--command]}} {{comando}} {{appid}}`

- Elenca tutti i giochi installati:

`protontricks {{[-l|--list]}}`

- Cerca l'ID App di un gioco per nome:

`protontricks {{[-s|--search]}} {{nome_gioco}}`

- Esegue un eseguibile nell'ambiente proton di un gioco specifico:

`protontricks-launch --appid {{appid}} {{percorso/eseguibile.exe}}`

- Mostra aiuto:

`protontricks {{[-h|--help]}}`
