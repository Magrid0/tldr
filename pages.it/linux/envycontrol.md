# envycontrol

> Utilità di commutazione GPU per laptop Nvidia Optimus.
> Maggiori informazioni: <https://github.com/bayasdev/envycontrol#%EF%B8%8F-usage>.

- Commuta tra diverse modalità GPU:

`sudo envycontrol {{[-s|--switch]}} {{nvidia|integrated|hybrid}}`

- Specifica manualmente il [d]isplay [m]anager:

`envycontrol --dm {{gdm|gdm3|sddm|lightdm}}`

- Controlla la modalità GPU corrente:

`sudo envycontrol {{[-q|--query]}}`

- Reimposta le impostazioni:

`sudo envycontrol --reset`

- Mostra aiuto:

`envycontrol {{[-h|--help]}}`

- Mostra versione:

`envycontrol {{[-v|--version]}}`
