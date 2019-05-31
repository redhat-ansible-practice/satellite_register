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
satellite_host: "https://mysatellite.com
sat_key: mykey
sat_env: production
sat_org: "mylab"
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

