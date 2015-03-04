# The ansible-winbind role

This role configures winbind authentication on a Ubuntu Trusty or CentOS 7 host 

## Requirements

Ubuntu 14.04 Trusty Tahr or CentOS 7

## Role Variables

### Mandatory

* ``addomain``:  The domain  to join to, must be uppercase, eg EXAMPLE.TLD
* ``adworkgroup``:  The workgroup, usually the firsst part of the domain, must be uppercase, eg EXAMPLE
* ``adadminuser``:  Username of a user who has permissions to add hosts to AD, eg Administrator
* ``adadminpw``:  Password of the above specified user

## Author

Alvaro Aleman
