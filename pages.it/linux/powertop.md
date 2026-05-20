# powertop

> Ottimizza l'uso dell'energia della batteria.
> Maggiori informazioni: <https://github.com/fenrus75/powertop>.

- Calibra le misurazioni del consumo energetico:

`sudo powertop --calibrate`

- Genera un report HTML del consumo energetico nella directory corrente:

`sudo powertop --html={{power_report.html}}`

- Ottimizza alle impostazioni ottimali:

`sudo powertop --auto-tune`

- Genera un report per un numero specificato di secondi (invece di 20 predefiniti):

`sudo powertop --time={{5}}`
