Repo\_ppa
=========

Role install PPA repository of choice.

Requirements
------------

Works only on Ubuntu.

Role Variables
--------------

name: Name of ppa repository.
state: 
  - present: Ensure repository is available (default)
  - absent: Ensure repository is not available.

Example Playbook
----------------

    - hosts: nginx_servers
      roles:
         - { role: davidkarban.repo_ppa, name: "ppa:nginx/stable" }
         - { role: davidkarban.repo_ppa, name: "ppa:brightbox/ruby-ng", state: "absent" }

License
-------

GPLv3

Author Information
------------------

email: david@karban.eu

github: davidkarban

web: www.karban.eu

