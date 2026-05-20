# evtest

> Mostra le informazioni dai driver dei dispositivi di input.
> Maggiori informazioni: <https://manned.org/evtest>.

- Elenca tutti i dispositivi di input rilevati e seleziona uno per il monitoraggio:

`sudo evtest`

- Mostra gli eventi da un dispositivo di input specifico:

`sudo evtest /dev/input/event{{numero}}`

- Acquisisce il dispositivo in modo esclusivo, impedendo ad altri client di ricevere eventi:

`sudo evtest --grab /dev/input/event{{numero}}`

- Interroga lo stato di un tasto o pulsante specifico su un dispositivo di input:

`sudo evtest --query /dev/input/event{{numero}} {{tipo_evento}} {{codice_evento}}`
