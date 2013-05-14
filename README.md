AnsibleWorks
============

AnsibleWorks is a GUI and REST API on top of core Ansible.

AnsibleWorks is commercial software, for use only under license.

This source code is not for distribution.

Technology
==========

* Ansible
* Django (a python web framework)
* Django REST Framework
* Celery (a python task engine)
* PostgreSQL
* Angular.js

Getting Things Installed
========================

See the ansible-doc repo

Accessing the UI
================

The UI is installed under lib/static/web. After starting the django server
(i.e. make runserver), access the ui from a web browser at:

http://127.0.0.1:8013/static/web/app/index.html

(routes and formal installation steps including Apache proxying pending)



