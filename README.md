Repo\_ppa
=========

Role install PPA repository of choice repository.

Requirements
------------

Works only on Ubuntu.

Role Variables
--------------

N/A.

Example Playbook
----------------

    - hosts: nginx_servers
      roles:
         - { role: davidkarban.repo_ppa, repo: "ppa:nginx/stable" }

License
-------

GPLv3

Author Information
------------------

email: david@karban.eu

github: davidkarban

web: www.karban.eu

