# instaloader

> Scarica immagini, video, didascalie e altri metadati da Instagram.
> Nota: sarà necessario fornire le credenziali di accesso a Instagram per scaricare media di alta qualità.
> Maggiori informazioni: <https://instaloader.github.io/cli-options.html>.

- Scarica un profilo:

`instaloader {{profile_name}}`

- Scarica i momenti salienti:

`instaloader --highlights {{profile_name}}`

- Scarica i post con geotag (se disponibili), senza interazione utente:

`instaloader {{[-q|--quiet]}} {{[-G|--geotags]}} {{profile_name}}`

- Specifica un user agent per le richieste HTTP:

`instaloader --user-agent {{user_agent}} {{profile_name}}`

- Specifica le credenziali di accesso e scarica i post (utile per profili privati):

`instaloader {{[-l|--login]}} {{username}} {{[-p|--password]}} {{password}} {{profile_name}}`

- Salta un target se il primo file scaricato è stato trovato (utile per aggiornare archivi Instagram):

`instaloader {{[-F|--fast-update]}} {{profile_name}}`

- Scarica storie e video IGTV (richiede l'accesso):

`instaloader {{[-l|--login]}} {{username}} {{[-p|--password]}} {{password}} {{[-s|--stories]}} --igtv {{profile_name}}`

- Scarica tutti i tipi di post (richiede l'accesso):

`instaloader {{[-l|--login]}} {{username}} {{[-p|--password]}} {{password}} {{[-s|--stories]}} --igtv --highlights {{profile_name}}`
