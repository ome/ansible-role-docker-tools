Docker Tools
============

[![Build Status](https://travis-ci.org/ome/ansible-role-docker-tools.svg)](https://travis-ci.org/ome/ansible-role-docker-tools)
[![Ansible Role](https://img.shields.io/ansible/role/41997.svg)](https://galaxy.ansible.com/ome/docker_tools/)

Install Python based docker tools, such as `docker-compose`.

This uses a mix of python modules from yum and modules installed globally with `pip`.

If your system hosts multiple services you should use a virtualenv (not currently implemented by this role) instead of installing docker-compose globally.


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
