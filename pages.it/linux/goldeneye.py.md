# goldeneye.py

> Strumento di test HTTP DoS.
> Maggiori informazioni: <https://github.com/jseidl/GoldenEye#usage>.

- Testa un sito web specifico:

`{{path/to/}}goldeneye.py {{url}}`

- Testa un sito web specifico con 100 user agent e 200 socket concorrenti:

`{{path/to/}}goldeneye.py {{url}} {{[-u|--useragents]}} 100 {{[-s|--sockets]}} 200`

- Testa un sito web specifico senza verificare il certificato SSL:

`{{path/to/}}goldeneye.py {{url}} {{[-n|--nosslcheck]}}`

- Testa un sito web specifico in modalità debug:

`{{path/to/}}goldeneye.py {{url}} {{[-d|--debug]}}`

- Mostra aiuto:

`{{path/to/}}goldeneye.py {{[-h|--help]}}`
