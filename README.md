mapr_resourcemanager
=========

Install mapr-resourcemanager.

Requirements
------------

Role Variables
--------------

```
  proxy_env:
    http_proxy: http://1.2.3.4:3128
    https_proxy: https://1.2.3.4:3128
```

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: resourcemanager
  max_fail_percentage: 0
  roles:
    - mapr-resourcemanager
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com
