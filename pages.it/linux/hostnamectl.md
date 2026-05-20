# hostnamectl

> Ottiene o imposta il nome host del computer.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/hostnamectl.html>.

- Ottiene il nome host del computer:

`hostnamectl`

- Imposta il nome host del computer:

`sudo hostnamectl set-hostname "{{hostname}}"`

- Imposta un nome host accattivante per il computer:

`sudo hostnamectl set-hostname --static "{{hostname.example.com}}" && sudo hostnamectl set-hostname --pretty "{{hostname}}"`

- Ripristina il nome host al suo valore predefinito:

`sudo hostnamectl set-hostname --pretty ""`
