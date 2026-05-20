# urpmf

> Trova file nei pacchetti e interroga informazioni su di essi in Mageia.
> Vedi anche: `urpmi`, `urpme`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmi.update`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmf.8.html>.

- Cerca pacchetti che contengono un file:

`urpmf {{nome_file}}`

- Cerca pacchetti che contengono [a] sia una parola chiave che un'altra nei loro riepiloghi:

`urpmf --summary {{parola_chiave1}} -a {{parola_chiave2}}`

- Cerca pacchetti che contengono [o] una parola chiave o un'altra nelle loro descrizioni:

`urpmf --description {{parola_chiave1}} -o {{parola_chiave2}}`

- Cerca pacchetti che non contengono una parola chiave nel loro nome ignorando la distinzione tra maiuscole/minuscole usando "|" come separatore di [c]ampo (":" per impostazione predefinita):

`urpmf --description ! {{parola_chiave}} -F'|'`
