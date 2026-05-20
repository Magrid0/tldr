# setenforce

> Commuta SELinux tra modalità enforcing e permissiva.
> Per abilitare o disabilitare SELinux, modifica `/etc/selinux/config` invece.
> Vedi anche: `getenforce`, `semanage-permissive`.
> Maggiori informazioni: <https://manned.org/setenforce>.

- Mette SELinux in modalità enforcing:

`setenforce {{1|Enforcing}}`

- Mette SELinux in modalità permissiva:

`setenforce {{0|Permissive}}`
