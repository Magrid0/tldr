# tshark

> Strumento di analisi dei pacchetti, versione CLI di Wireshark.
> Maggiori informazioni: <https://tshark.dev/#sitemap-in-tshark---help>.

- Monitora tutto su localhost:

`tshark`

- Cattura solo pacchetti che corrispondono a un filtro di cattura specifico:

`tshark -f '{{udp port 53}}'`

- Mostra solo pacchetti che corrispondono a un filtro di output specifico:

`tshark -Y '{{http.request.method == "GET"}}'`

- Decodifica una porta TCP usando un protocollo specifico (es. HTTP):

`tshark -d tcp.port=={{8888}},{{http}}`

- Specifica il formato dell'output catturato:

`tshark -T {{json|text|ps|...}}`

- Seleziona campi specifici da mostrare in output:

`tshark -T {{fields|ek|json|pdml}} -e {{http.request.method}} -e {{ip.src}}`

- Scrivi i pacchetti catturati in un file:

`tshark -w {{percorso/del/file}}`

- Analizza pacchetti da un file:

`tshark -r {{percorso/del/file.pcap}}`
