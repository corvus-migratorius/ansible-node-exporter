Role Name
=========

Deploy `prometheus/node_exporter` binary as a systemd unit.

Requirements
------------

None

Role Variables
--------------

`node_exp_bin_path`: where to put the binary (default: `/usr/bin`).

Dependencies
------------

None

Example Playbook
----------------

```yaml
roles:
    - role: prom_node_exp
      node_exp_ver: "1.6.1"
```

License
-------

BSD

Author Information
------------------

corvus-migratorius@proton.me
