etcd Ansible role
=================

Install and configured a etcd service.

Role Tags
---------

 * install
 * configure
 * deploy
 * test

Role Variables
--------------

See defaults/main.yml

Example Playbook
----------------


    - hosts: localhost
      roles:
         - role: etcd
           etcd_client_port: 2379
           etcd_peer_port: 2380

License
-------

MIT

Author Information
------------------

Based on https://github.com/kubernetes/contrib/ansible/roles/etcd
