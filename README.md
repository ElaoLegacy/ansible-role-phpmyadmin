WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


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
    localhost:
        auth_type:          cookie
        host:               "localhost"
        connect_type:       tcp
        compress:           "false"
        AllowNoPassword:    "false"
```

# TODO 

Add all the other PMA variables.