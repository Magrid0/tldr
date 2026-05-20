# i2cdump

> Scarica i registri di un dispositivo I2C.
> Vedi anche: `i2cdetect`, `i2cget`, `i2cset`.
> Nota: tutti gli indirizzi devono essere specificati in esadecimale.
> Maggiori informazioni: <https://manned.org/i2cdump>.

- Scarica tutti i registri di un dispositivo I2C:

`i2cdump {{i2cbus}} {{device_address}}`

- Scarica tutti i registri di un dispositivo I2C senza chiedere conferma:

`i2cdump -y {{i2cbus}} {{device_address}}`

- Scarica tutti i registri di un dispositivo I2C usando una modalità specifica:

`i2cdump {{i2cbus}} {{device_address}} {{b|w|c|s|i}}`

- Scarica i registri da `start` a `end` di un dispositivo I2C:

`i2cdump -r {{start}}-{{end}} {{i2cbus}} {{device_address}}`
