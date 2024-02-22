Dependency graph:

```
$ cargo tree

helloworld v0.1.0 (/home/schubart/projects/helloworld)
└── tokio v1.36.0
    ├── bytes v1.5.0
    ├── libc v0.2.153
    ├── mio v0.8.10
    │   └── libc v0.2.153
    ├── num_cpus v1.16.0
    │   └── libc v0.2.153
    ├── parking_lot v0.12.1
    │   ├── lock_api v0.4.11
    │   │   └── scopeguard v1.2.0
    │   │   [build-dependencies]
    │   │   └── autocfg v1.1.0
    │   └── parking_lot_core v0.9.9
    │       ├── cfg-if v1.0.0
    │       ├── libc v0.2.153
    │       └── smallvec v1.13.1
    ├── pin-project-lite v0.2.13
    ├── signal-hook-registry v1.4.1
    │   └── libc v0.2.153
    ├── socket2 v0.5.5
    │   └── libc v0.2.153
    └── tokio-macros v2.2.0 (proc-macro)
        ├── proc-macro2 v1.0.78
        │   └── unicode-ident v1.0.12
        ├── quote v1.0.35
        │   └── proc-macro2 v1.0.78 (*)
        └── syn v2.0.50
            ├── proc-macro2 v1.0.78 (*)
            ├── quote v1.0.35 (*)
            └── unicode-ident v1.0.12
```