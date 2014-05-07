avanov.{{ cookiecutter.name }}
==============================

{{ cookiecutter.description }}

Install it with the following command:

```bash
$ ansible-galaxy install avanov.{{ cookiecutter.name }}
```

Requirements
------------

None

Role Variables
--------------

Here is the list of all variables and their default values:



Dependencies
------------

None

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - {role: avanov.{{ cookiecutter.name }} }

License
-------

MIT

Author Information
------------------

{{ cookiecutter.author }} ({{ cookiecutter.author_url }})
