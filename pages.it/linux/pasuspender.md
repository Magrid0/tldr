# pasuspender

> Sospende temporaneamente `pulseaudio` mentre un altro comando è in esecuzione per consentire l'accesso ad alsa.
> Maggiori informazioni: <https://manned.org/pasuspender>.

- Sospende PulseAudio durante l'esecuzione di `jackd`:

`pasuspender -- {{jackd --driver alsa --device hw:0}}`
