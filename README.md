Role Name
=========

A brief description of the role goes here.

Requirements
------------

On RedHat/CentOS systems, make sure you have the EPEL repository installed.


Role Variables
--------------

The default values for the variables are set in `defaults/main.yml`:

```
  ---
  security_fail2ban_enabled: true
  security_fail2ban_bantime: 600
  security_fail2ban_maxretry: 5
  security_fail2ban_jail_configuration: []
```


Dependencies
------------

None

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: maricaantonacci.security  }

License
-------

BSD

Author Information
------------------

Marica Antonacci (marica.antonacci@ba.infn.it)
