# sam

> AWS Serverless Application Model (SAM) CLI.
> Maggiori informazioni: <https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/using-sam-cli-corecommands.html>.

- Inizializza un'applicazione serverless:

`sam init`

- Inizializza un'applicazione serverless con un runtime specifico:

`sam init {{[-r|--runtime]}} {{python3.7}}`

- Impacchetta un'applicazione SAM:

`sam package`

- Compila il codice della funzione Lambda:

`sam build`

- Esegue l'applicazione serverless localmente:

`sam local start-api`

- Distribuisce un'applicazione AWS SAM:

`sam deploy`
