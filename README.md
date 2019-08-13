activemq
=========

[![Build Status](https://travis-ci.org/sirReeall/activemq.svg?branch=master)](https://travis-ci.org/sirReeall/activemq)

Downloads activemq 5.15.6 from apache and unpacks to specified activemq_install_dir directory.

A dedicated user activemq_user is also created and made the ownwer of the unpacked binaries.

This user can then be used to start activemq.

Role Variables
--------------
The username created and configured to own the installation

activemq_user

The location where activemq is installed:

activemq_install_dir


The follow variables are used to define the version of activemq downloaded:

activemq_major_version

activemq_minor_version

activemq_hotfix_version

License
-------

Free
