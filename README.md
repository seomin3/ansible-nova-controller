openstack-nova-controller
=========================

**Status**
* [![Build Status](https://travis-ci.org/openstack-ansible-galaxy/openstack-nova-controller.svg?branch=master)](https://travis-ci.org/openstack-ansible-galaxy/openstack-nova-controller) on master branch
* [![Build Status](https://travis-ci.org/openstack-ansible-galaxy/openstack-nova-controller.svg?branch=development)](https://travis-ci.org/openstack-ansible-galaxy/openstack-nova-controller) on development branch

OpenStack Nova Cotroller Node role


Requirements
------------

A RabbitMQ server.
A MySQL .

Role Variables
--------------


Dependencies
------------

ansible-repos


Example Playbook
----------------

    - hosts: controller001
      roles:
        - role: openstack-nova-controller
          (...)



License
-------

Apache

Author Information
------------------

Abel Boldú <abel.boldu@gmx.com>
