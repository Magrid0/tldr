# powertop2tuned

> Crea profili TuneD dalle raccomandazioni di PowerTOP.
> Parte di `tuned-utils`.
> Vedi anche: `powertop`, `tuned-adm`.
> Maggiori informazioni: <https://docs.fedoraproject.org/en-US/quick-docs/automatic-power-management-power2top/>.

- Crea un nuovo profilo TuneD basato sulle raccomandazioni attuali di PowerTOP:

`sudo powertop2tuned {{nome_profilo}}`

- Crea un nuovo profilo e abilita la maggior parte delle raccomandazioni automaticamente:

`sudo powertop2tuned {{[-e|--enable]}} {{nome_profilo}}`

- Crea un profilo da un report HTML PowerTOP esistente:

`sudo powertop2tuned {{[-i|--input]}} {{percorso/report.html}} {{nome_profilo}}`

- Crea un nuovo profilo in una directory specifica:

`sudo powertop2tuned {{[-o|--output]}} {{percorso/directory}} {{nome_profilo}}`

- Crea un nuovo profilo senza unire il profilo attivo:

`sudo powertop2tuned {{[-n|--new-profile]}} {{nome_profilo}}`

- Unisci raccomandazioni con un profilo esistente specifico:

`sudo powertop2tuned {{[-m|--merge-profile]}} {{profilo_esistente}} {{nome_profilo}}`

- Forza la sovrascrittura di una directory di profilo esistente:

`sudo powertop2tuned {{[-f|--force]}} {{nome_profilo}}`
