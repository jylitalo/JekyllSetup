JekyllSetup
===========

Jekyll setup with multiple git repositories.

![Build status](https://travis-ci.org/jylitalo/JekyllSetup.svg?branch=master) 

Requirements
------------

Ruby

Role Variables
--------------

* content_repo: repo that has pages and posts
* images_dir: directory, which should have all images
* override_dir: _config.yml and whatever needs to be overrided from default blog
* colorbox_theme: colorbox theme for blog
* colorbox_i18n: localisation file for colorbox

Dependencies
------------

None

Example Playbook
----------------

    - hosts: server
      tasks:
      - include_role
        name: JekyllSetup
      vars:
        content_repo: "..."

License
-------

MIT

Author Information
------------------

Juha Ylitalo, juha.ylitalo@gmail.com, http://www.ylitalot.com/
