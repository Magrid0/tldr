# systemd-notify

> Notifica al gestore dei servizi il completamento dell'avvio e altre modifiche dello stato del demone.
> Questo comando è inutile al di fuori degli script di servizio systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-notify.html>.

- Notifica a systemd che il servizio ha completato l'inizializzazione ed è completamente avviato. Dovrebbe essere invocato quando il servizio è pronto per accettare richieste in arrivo:

`systemd-notify --booted`

- Segnala a systemd che il servizio è pronto per gestire connessioni in entrata o eseguire le sue attività:

`systemd-notify --ready`

- Fornisce un messaggio di stato personalizzato a systemd (questa informazione viene mostrata da `systemctl status`):

`systemd-notify --status "{{Aggiungi qui un messaggio di stato personalizzato...}}"`
