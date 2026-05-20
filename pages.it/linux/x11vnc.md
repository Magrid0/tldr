# x11vnc

> Un server VNC che abilita VNC su un server di visualizzazione esistente.
> In modo predefinito, il server termina automaticamente quando tutti i client si disconnettono.
> Maggiori informazioni: <https://manned.org/x11vnc>.

- Avvia un server VNC che permette a più client di connettersi:

`x11vnc -shared`

- Avvia un server VNC in sola visualizzazione e che non termina quando l'ultimo client si disconnette:

`x11vnc -forever -viewonly`

- Avvia un server VNC su un display e schermo specifici (entrambi partono da indice zero):

`x11vnc -display :{{display}}.{{screen}}`

- Avvia un server VNC sullo schermo predefinito del terzo display:

`x11vnc -display :{{2}}`

- Avvia un server VNC sul secondo schermo del primo display:

`x11vnc -display :{{0}}.{{1}}`
