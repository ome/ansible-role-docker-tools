Docker Tools
============

[![Actions Status](https://github.com/ome/ansible-role-logrotate/workflows/Molecule/badge.svg)](https://github.com/ome/ansible-role-docker-tools/actions)
[![Ansible Role](https://img.shields.io/badge/ansible--galaxy-docker_tools-blue.svg)](https://galaxy.ansible.com/ui/standalone/roles/ome/docker_tools/)

Install Python based docker tools, such as `docker-compose`.

This uses a mix of python modules from dnf and modules installed globally with `pip`.

If your system hosts multiple services you should use a virtualenv (not currently implemented by this role) instead of installing docker-compose globally.


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
