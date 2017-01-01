andrewrothstein.emacs-config
=========

A role to my [Emacs](https://www.gnu.org/software/emacs/) configuration

Requirements
------------

Assumes emacs is already installed. Consider [andrewrothstein.emacs](https://galaxy.ansible.com/andrewrothstein/emacs/)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.emacs-config
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
