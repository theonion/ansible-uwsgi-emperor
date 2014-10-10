uwsgi-emperor
=========

This role installs and configures uWSGI in Emperor mode.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

`uwsgi_install_method`: Should be one of "pip", "apt" or "source"
`uwsgi_version`: Defaults to the latest, but otherwise installs the specified version

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: theonion.uwsgi-emperor, uwsgi_install_method: pip }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
