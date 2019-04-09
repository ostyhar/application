Application
=========

Install PHP app from deb file and create app user
Run phpunit if env.testing exists
Build env file from base exaple and dict

Role Variables
--------------

app_user: www-data
app_group: www-data
app_directory: /app/install/here
app_clean_dev_dependecies: true
app_deb_package: file_to_install.deb

Example Playbook
----------------

    - hosts: servers
      roles:
         - entanet-devops.application

License
-------

BSD
