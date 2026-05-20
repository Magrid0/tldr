# systemctl isolate

> Avvia l'unità specificata con le sue dipendenze e ferma tutte le altre.
> Ignora le unità che hanno `IgnoreOnIsolate=yes`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#isolate%20UNIT>.

- Passa a un target (assunto `.target` se non viene fornita estensione):

`systemctl isolate {{target}}`

- Passa esplicitamente al target grafico:

`systemctl isolate graphical.target`

- Passa alla modalità di ripristino (utente singolo):

`systemctl isolate rescue.target`

- Passa alla modalità di emergenza:

`systemctl isolate emergency.target`
