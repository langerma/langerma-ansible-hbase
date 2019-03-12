# ansible-bigtop-hbase

## sample playbook
```yml
- hosts: all
  remote_user: vagrant
  become: true

  roles:
    - role: ansible-bigtop-hdfs
```
