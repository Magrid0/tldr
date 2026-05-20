# cgcreate

> Crea cgroups, utilizzati per limitare, misurare e controllare le risorse utilizzate dai processi.
> I tipi di `cgroups` possono essere `memory`, `cpu`, `net_cls`, ecc.
> Maggiori informazioni: <https://manned.org/cgcreate>.

- Crea un nuovo [g]ruppo:

`cgcreate -g {{group_type}}:{{group_name}}`

- Crea un nuovo [g]ruppo con più tipi di cgroup:

`cgcreate -g {{group_type1}},{{group_type2}}:{{group_name}}`

- Crea un sottogruppo:

`mkdir /sys/fs/cgroup/{{group_type}}/{{group_name}}/{{subgroup_name}}`
