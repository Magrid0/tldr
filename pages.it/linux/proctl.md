# proctl

> Gestisce licenze e lingue dei progetti, passando tra licenze template.
> Maggiori informazioni: <https://github.com/CreativeCodeCat/proctl>.

- Elenca le licenze disponibili:

`proctl {{[-ll|-list-licenses]}}`

- Elenca le lingue disponibili:

`proctl {{[-lL|-list-languages]}}`

- Sceglie una licenza in un menu FZF:

`proctl {{[-pl|-pick-license]}}`

- Sceglie una lingua in un menu FZF:

`proctl {{[-pL|-pick-language]}}`

- Rimuove tutte le licenze dal progetto corrente:

`proctl {{[-r|-remove-license]}}`

- Crea un nuovo template di licenza:

`proctl {{[-t|-new-template]}}`

- Elimina una licenza dai template:

`proctl {{[-R|-delete-license]}} {{@nome_licenza1 @nome_licenza2 ...}}`

- Mostra aiuto:

`proctl {{[-h|-help]}}`
