Ansible-Role Vector for CentOS 7
=========

Role installs Vector on CentOS 7. 

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

* The version vector to install.
```yml
  vector_version: 0.31.0
```
* Change server name clickhouse ['clickhouse-01']
```yml
  vector_conf_endpoint: http://{{ hostvars['clickhouse-01'].ansible_default_ipv4.address }}:8123

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- name: Install Vector
  hosts: vector
  roles:
    - vector-role
```


License
-------

MIT

Author Information
------------------

samborch
