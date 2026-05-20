# lid

> Interroga un database ID per token corrispondenti a un pattern.
> Nota: Un database ID deve essere prima creato usando `mkid`.
> Maggiori informazioni: <https://www.gnu.org/software/idutils/manual/idutils.html#lid-invocation>.

- Elenca tutti i token e le loro posizioni nei file nel database ID:

`lid`

- Trova i file contenenti un token specifico:

`lid {{token}}`

- Trova token corrispondenti a un pattern, ignorando le maiuscole:

`lid {{[-i|--ignore-case]}} {{token}}`

- Trova token corrispondenti a un'espressione `regex` estesa:

`lid {{[-r|--regexp]}} "{{pattern}}"`

- Output delle righe corrispondenti in formato grep-style:

`lid {{[-R|--result]}} grep {{token}}`

- Trova token che appaiono una sola volta (utile per trovare definizioni inutilizzate):

`lid {{[-F|--frequency]}} 1`
