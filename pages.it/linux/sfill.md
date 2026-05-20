# sfill

> Sovrascrive in modo sicuro lo spazio libero e gli inode della partizione in cui risiede la directory specificata.
> Maggiori informazioni: <https://manned.org/sfill>.

- Sovrascrive lo spazio libero e gli inode di un disco con 38 scritture (lento ma sicuro):

`sfill /{{percorso/della_directory_del_disco_montato}}`

- Sovrascrive lo spazio libero e gli inode di un disco con 6 scritture (veloce ma [m]eno sicuro) e mostra lo stato ([v]erbose):

`sfill -l -v /{{percorso/della_directory_del_disco_montato}}`

- Sovrascrive lo spazio libero e gli inode di un disco con 1 scrittura (molto veloce ma [m]eno sicuro) e mostra lo stato:

`sfill -ll -v /{{percorso/della_directory_del_disco_montato}}`

- Sovrascrive solo lo spazio libero di un d[I]sco:

`sfill -I /{{percorso/della_directory_del_disco_montato}}`

- Sovrascrive solo gli [i]node liberi di un disco:

`sfill -i /{{percorso/della_directory_del_disco_montato}}`
