# ntpd

> Il demone NTP (Network Time Protocol) ufficiale per sincronizzare l'orologio di sistema con server remoti o orologi di riferimento locali.
> Maggiori informazioni: <https://manned.org/ntpd>.

- Avvia il demone:

`sudo ntpd`

- Sincronizza l'ora di sistema con server remoti una sola volta (esce dopo la sincronizzazione):

`sudo ntpd --quit`

- Sincronizza una sola volta permettendo regolazioni "Grandi":

`sudo ntpd --panicgate --quit`
