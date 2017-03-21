influxdb
================

deploy influxdb

Role Variables
--------------
If you want to enable web ui, set **influxdb_admin_enabled** to "true"

> influxdb_admin_enabled: "true"

Default web ui port is 8083, if you want to set web ui port, set **influxdb_admin_bind_address**

> influxdb_admin_bind_address: ":8089"


Example Playbook
----------------

```
- hosts: influxdb
  become: true
  roles:
    - /path/to/ansible-galaxy-influxdb
```

License
-------

MIT
