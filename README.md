vector
=========

This role installs Vector and optionally configures lighthouse sink for it
RedHat an debian OS families supported.
Requirements
------------

- none

Role Variables
--------------

- vector_version - minimal Vector version to install
- vector_configure_click_sink - configure clickhouse sink if true 
- vector_click_host - clickhouse server hostname
- vector_click_db - database name to use
- vector_click_table - table name to use

Dependencies
------------

none

Example Playbook
----------------
```yaml
    - hosts: servers
      roles:
         - vector
```
License
-------

BSD

Author Information
------------------


