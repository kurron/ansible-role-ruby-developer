Role Name
=========

Installation of tools than any self-respecting Ruby developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* ruby_rvm_install: true
* ruby_rubymine_install: true
* ruby_rubymine_version: 2016.2.4

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.ruby-developer, ruby_rvm_install: false, ruby_rubymine_version: 2016.2.4 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
