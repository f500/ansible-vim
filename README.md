Vim
========

Install Vim, set vimrc and use update-alternatives to add vim

Requirements
------------

Debian Bullseye / Bookworm with the package python-pycurl and python-software-properties installed.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: f500.vim }

Linting
-------
Github actions will check this role with ansible-lint. To run this locally, you will need to follow the following steps:

```bash
brew install ansible-lint
brew install yamllint
ansible-lint
```

to fix the linting errors, run:

```bash
ansible-lint --fix
```

License
-------

LGPL-3.0

This role includes a module called **update_alternatives** written by Philipp Grau, released
under the GPL license.

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
