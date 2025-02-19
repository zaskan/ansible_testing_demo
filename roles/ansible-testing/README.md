Role Name
=========

This role download an Ansible collection and perform lint and molecule tests over it. It can also sign the ansible code and upload the artifact to Automation Hub.


Role Variables
--------------

project_git_url: Git url containing the ansible project to test 
project_dir: Local directory to download the project

Dependencies
------------

https://github.com/zaskan/demos.utils.git

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
