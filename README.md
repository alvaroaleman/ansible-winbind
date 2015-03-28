# The ansible-winbind role

This role configures winbind authentication on a Ubuntu Trusty or CentOS 7 host 

## Requirements

One of either

- Ubuntu 14.04
- Debian 8
- Centos 7

## Role Variables

### Mandatory

* ``addomain``:  The domain  to join to, must be uppercase, eg ``EXAMPLE.TLD``
* ``adworkgroup``:  The workgroup, usually the first part of the domain, must be uppercase, eg ``EXAMPLE``
* ``adadminuser``:  Username of a user who has permissions to add hosts to AD, eg ``Administrator``
* ``adadminpw``:  Password of the above specified user

### Original Author

Alvaro Aleman
