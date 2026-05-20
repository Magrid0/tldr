# physlock

> Blocca tutte le console e i terminali virtuali.
> Maggiori informazioni: <https://github.com/xyb3rt/physlock#usage>.

- Blocca ogni console (richiede l'utente corrente o root per sbloccare):

`physlock`

- Silenzia i messaggi del kernel sulla console mentre è bloccata:

`physlock -m`

- Disabilita il meccanismo SysRq mentre è bloccato:

`physlock -s`

- Mostra un messaggio prima della richiesta password:

`physlock -p "{{Bloccato!}}"`

- Crea un fork e scollega physlock (utile per script di sospensione o ibernazione):

`physlock -d`
