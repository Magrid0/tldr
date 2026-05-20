# asterisk

> Esegue e gestisce istanze di server telefonici e di centralino (telefono).
> Maggiori informazioni: <https://docs.asterisk.org/Operation/>.

- [r]iconnette a un server in esecuzione e attiva la registrazione a 3 livelli di [v]erbosità:

`asterisk -r -vvv`

- [r]iconnette a un server in esecuzione, esegue un singolo comando e ritorna:

`asterisk -r -x "{{comando}}"`

- Mostra i client chan_SIP (telefoni):

`asterisk -r -x "sip show peers"`

- Mostra chiamate e canali attivi:

`asterisk -r -x "core show channels"`

- Mostra le cassette vocali:

`asterisk -r -x "voicemail show users"`

- Termina un canale:

`asterisk -r -x "hangup request {{id_canale}}"`

- Ricarica la configurazione di chan_SIP:

`asterisk -r -x "sip reload"`
