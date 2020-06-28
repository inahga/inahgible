gnome-workstation
=========

Installs some extensions and applies some sane settings to GNOME. After applying, you must log out and log back in.

Requirements
------------

- GNOME already installed. 

Testing
------------
```
ansible localhost -m include_role -a name=gnome-workstation
```
