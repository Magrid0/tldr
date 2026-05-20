# pwn

> Libreria di sviluppo Exploit progettata per prototipazione rapida.
> Maggiori informazioni: <https://docs.pwntools.com/en/stable/commandline.html>.

- Converte il codice assembly dato in `bytes`:

`pwn asm "{{xor edi, edi}}"`

- Crea un pattern ciclico del numero specifico di caratteri:

`pwn cyclic {{numero}}`

- Codifica i dati dati nel sistema esadecimale:

`pwn hex {{deafbeef}}`

- Decodifica i dati dati dall'esadecimale:

`pwn unhex {{6c4f7645}}`

- Stampa un shellcode Linux x64 per eseguire una shell:

`pwn shellcraft {{amd64.linux.sh}}`

- Controlla le impostazioni di sicurezza binarie per il file ELF dato:

`pwn checksec {{percorso/del/file}}`

- Controlla aggiornamenti di Pwntools:

`pwn update`

- Mostra versione:

`pwn version`
