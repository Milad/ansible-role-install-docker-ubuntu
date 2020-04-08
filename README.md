ansible-role-install-docker-ubuntu
=========

Install Docker on Ubuntu bionic according to the [digitalocean's instructions](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04) and [ops.tips](https://ops.tips/blog/docker-ansible-role/). 

Requirements
------------

None

Role Variables
--------------

Check the file [defaults/main.yml](./defaults/main.yml) for details.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Milad Kawas. @miladkawas
