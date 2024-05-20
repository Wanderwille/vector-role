vector-role 
=========

Install vector role

<!-- Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required. -->

Role Variables
--------------

- vector_conf_dir: "/etc/vector/"

- vector_version: 0.36.0

<!-- Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles. -->

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vector-01
      roles:
         - { role: vector-role }

License
-------

MIT

Author Information
------------------

Krasil'nikov Leonid (wineperm)