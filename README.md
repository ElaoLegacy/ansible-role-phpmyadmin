# Ansible

Ansible Role - phpMyAdmin
==================

A role for phpMyAdmin installation and configuration

## Requirements

* [Ansible 1.7.2+](http://docs.ansible.com/intro_installation.html)
* [Sshpass](https://gist.github.com/arunoda/7790979)

## Defining your configuration like following:

```
---

elao_pma:
    version:            "RELEASE_4_3_3"
    root_dir:           /srv/www/pma

elao_pma_servers:
    db1:
        auth_type:          cookie
        host:               "db-1.tuxboard.local"
        connect_type:       tcp
        compress:           "false"
        AllowNoPassword:    "true"
```

# TODO 

Add all the other PMA variables.