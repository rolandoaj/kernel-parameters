Kernel parameters
=========

Add configurations to sysctl.conf enforcing network security


Role Variables
--------------

All configuratrions are in templates/sysctl.j2


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: servers
  gather_facts: yes
  gather_subset: min
  roles:
     - role: roles/kernel-parameters

License
-------

BSD

Author Information
------------------

Developed by Rolando Antonio https://www.linkedin.com/in/rolando-ant-j/
