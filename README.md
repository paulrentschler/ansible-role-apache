paulrentschler.apache
======================

[![MIT licensed][mit-badge]][mit-link]

Installs and configures the Apache HTTP server on Ubuntu or RedHat Linux.

RedHat/CentOS support is limited but should work for common situations.


Requirements
------------

None.


Role Variables
--------------

The following variables are available with defaults defined in `defaults/main.yml`:



Dependencies
------------

None.


Example Playbook
----------------

Simple example:

    - hosts: all
      roles:
        - role: paulrentschler.apache
          vars:
            apache_admin_email: webadmin@example.com
            apache_ssl_certs_path: "certs/"
            apache_use_ssl: no
            apache_vhosts:
              - hostname: "www"
                domain: "example.com"
                priority: 100
                enable: yes
                docroot: yes
                use_www: no
                use_ssl: no


License
-------

[MIT][mit-link]


Author Information
------------------

Created by Paul Rentschler in 2021.


[mit-badge]: https://img.shields.io/badge/license-MIT-blue.svg
[mit-link]: https://github.com/paulrentschler/ansible-role-apache/blob/master/LICENSE
