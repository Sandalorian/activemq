activemq_install
=========
Downloads and installs activemq. Will create a user named activemq which should be used to run the activemq script.

Role Variables
--------------

The follow variables are used to define the version of activemq downloaded:
activemq_major_version 
activemq_minor_version
activemq_hotfix_version

The following variable should not need to be modified as they a constructed using the above three version related variables:
activemq_version
activemq_file_name
activemq_download_url: "https://archive.apache.org/dist/activemq/{{ activemq_version }}/{{ activemq_file_name }}"

The location where activemq is installed:
activemq_install_dir

The username created and configured to own the installation
activemq_user

License
-------

Free
