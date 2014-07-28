foreman-client-tools
====================

Client tools for The Foreman:

* puppet-foreman: Registers host and deploys puppet configuration.

Note
----

To register existing host into Foreman, you only need to configure Puppet and
configure Puppet Master with Foreman ENC. Once report is sent, Host entry is
created in Foreman automatically.

This tool is a simple wrapper to automate the Puppet configuration file
deployment via Foreman templates and integration with subscription-manager
(utility from RHEL).

THIS IS WORKING IN PROGRESS. It won't work with Foreman (patches needed).

Documentation
-------------

See man/ subdirectory of the git repo.

License
-------

GNU GPL v3+, see LICENSE.
