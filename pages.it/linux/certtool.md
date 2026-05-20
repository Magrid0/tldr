# certtool

> Genera e gestisce certificati X.509, chiavi e strutture PKI utilizzando GnuTLS.
> Maggiori informazioni: <https://gnutls.org/manual/gnutls.html#certtool-Invocation>.

- Genera una chiave privata e la salva in un file:

`certtool {{[-p|--generate-privkey]}} --outfile {{path/to/private.key}}`

- Genera un certificato autofirmato usando una chiave privata e un file modello:

`certtool {{[-s|--generate-self-signed]}} --load-privkey {{path/to/private.key}} --template {{path/to/info.template}} --outfile {{path/to/certificate.crt}}`

- Genera una richiesta di firma del certificato (CSR):

`certtool {{[-q|--generate-request]}} --load-privkey {{path/to/private.key}} --template {{path/to/info.template}} --outfile {{path/to/request.csr}}`

- Genera un certificato di autorità di certificazione (CA):

`certtool {{[-s|--generate-self-signed]}} --load-privkey {{path/to/ca.key}} --template {{path/to/ca.template}} --outfile {{path/to/ca.crt}}`

- Verifica un certificato rispetto a un certificato CA:

`certtool --verify --infile {{path/to/certificate.crt}} --load-ca-certificate {{path/to/ca.crt}}`
