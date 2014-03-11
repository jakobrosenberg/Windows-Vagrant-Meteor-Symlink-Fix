Windows-Vagrant-Meteor-Symlink-Fix
==================================

This script mounts new directories to ``.meteor/local`` and ``packages`` in any Meteor project. The new location of these directories is ``/home/[path-to-your-app]`` ie. ``/home/vagrant/myapp``.


Install
-------
Run the command below in your shell
``wget --directory-prefix /usr/bin https://raw.githubusercontent.com/jakobrosenberg/Windows-Vagrant-Meteor-Symlink-Fix/master/fixmeteor && chmod +x /usr/bin/fixmeteor``

Uninstall
---------
Run the command below in your shell
``rm /usr/bin/fixmeteor``

Usage
-----
Type ``fixmeteor`` from any Meteor app directory.

Example:
```
meteor create my_app
cd my_app
fixmeteor
```
