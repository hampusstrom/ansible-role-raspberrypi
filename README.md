Role Name
=========

This role configures raspberry pi devices after my own needs.

* Disables bluetooth to reduce bluetooth interference in my home. (I don't use the bluetooth on RPI)
* Installs and configures log2ram, as to not wear out my SD Card.

Requirements
------------
Has to be run against a log2ram supported platform.
See https://github.com/azlux/log2ram

Role Variables
--------------

See defaults/main.yml

Dependencies
------------
N/A

Example Playbook
----------------

    - hosts: rpi
      roles:
         - hampusstrom.raspberrypi

License
-------
MIT

