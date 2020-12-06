# Ansible-role-Tinytinyrss

The purpose of this role is to have fun with ansible and molecule. It installs apache, mariadb and tinytiny-rss.

Role Name
=========
Tinytinyrss

Requirements
------------
No special requirements

Role Variables
--------------
TODO

vars_sensitive.yml :
```
# Mysql root login info
database_rootpwd:

# Tinytiny rss info
database_ttrss_user:
database_ttrss_pwd:
database_ttrss_dbname:
```

Dependencies
------------
TODO

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
A bored sysadmin doing it for fun

Todo
-------
- Check for update to "Service is in unknown state" bug : https://github.com/ansible/ansible/issues/71528
- RSS feed update with cron job
- TLS cert / LetsEncrypt
- Backup tasks
- Update tasks