openmicroscopy.infra
====================

Meta-package for installing compatible sets of roles.

Requirements
------------

This role consists solely of dependencies on other ansible
roles (see the meta/main.yml file). When a significant bump
to any dependency occurs, the major version of this role
will also be bumped.

Role Variables
--------------

None

Dependencies
------------

Many

Example
-------

Primarily intended as a simple way of installing several
OME roles in one shot, either from the command-line:

    ansible-galaxy install openmicroscopy.infra

or from a requirements.yml file:

    - src: openmicroscopy.infra

License
-------

BSD

Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
