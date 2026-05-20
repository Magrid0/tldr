# iscsiadm

> Gestisce sessioni, nodi e scoperta iSCSI.
> Maggiori informazioni: <https://manned.org/iscsiadm>.

- Mostra le sessioni iSCSI attive:

`sudo iscsiadm {{[-m|--mode]}} session`

- Elenca tutti i nodi iSCSI conosciuti:

`sudo iscsiadm {{[-m|--mode]}} node`

- Scopre i target iSCSI disponibili su un portale (senza autenticazione):

`sudo iscsiadm {{[-m|--mode]}} discovery {{[-t|--type]}} sendtargets {{[-p|--portal]}} {{ip_address}}`

- Accede a un target iSCSI specifico senza autenticazione:

`sudo iscsiadm {{[-m|--mode]}} node {{[-T|--targetname]}} {{iqn}} {{[-p|--portal]}} {{ip_address}}:3260 {{[-l|--login]}}`

- Esce da un target iSCSI specifico:

`sudo iscsiadm {{[-m|--mode]}} node {{[-T|--targetname]}} {{iqn}} {{[-p|--portal]}} {{ip_address}}:3260 {{[-u|--logout]}}`

- Crea un nodo iSCSI quando la scoperta è bloccata (per autenticazione CHAP):

`sudo iscsiadm {{[-m|--mode]}} node {{[-o|--op]}} new {{[-T|--targetname]}} {{iqn}} {{[-p|--portal]}} {{ip_address}}:3260`

- Configura l'autenticazione CHAP per un target iSCSI:

`sudo iscsiadm {{[-m|--mode]}} node {{[-T|--targetname]}} {{iqn}} {{[-p|--portal]}} {{ip_address}}:3260 {{[-o|--op]}} update {{[-n|--name]}} node.session.auth.authmethod {{[-v|--value]}} CHAP`
