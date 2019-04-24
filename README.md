Satellite_Register
=========

Register your host to Satellite. This role installs the Katello CA RPM from Satellite then registers to the appropriate repositories using an activation key.

Requirements
------------

- activation key
- organization
- 
Role Variables
--------------
```
satellite_host: "https://satellite6-lab.deadpool.od4apps.com"
sat_key: jbosseap7
sat_env: production
sat_org: "ODFL-Lab"
```


Dependencies
------------


Example Playbook
----------------

    - hosts: myserver
      roles:
         - satellite_reg

License
-------


Author Information
------------------

