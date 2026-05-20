# modetest

> Diagnostica Direct Rendering Manager e Kernel Mode Setting.
> Maggiori informazioni: <https://xilinx-wiki.atlassian.net/wiki/spaces/A/pages/18841850/Video_Mixer#modetest>.

- Elenca i connettori e le loro modalità disponibili:

`modetest -c`

- Elenca i connettori e le loro modalità disponibili per un driver specifico:

`modetest -M {{mgag200}} -c`

- Imposta la risoluzione di un connettore:

`sudo modetest -M {{mgag200}} -s {{connector_id}}:{{1600}}x{{1200}}`
