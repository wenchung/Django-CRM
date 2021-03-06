Django-CRM
==========

Django CRM is opensourse CRM developed on django framework. It has all the basic features of CRM to start with. We welcome code contributions and feature requests via github.

.. list-table::
   :header-rows: 1
   :widths: 50 50 150 90
   :stub-columns: 1

   *  -  Build Status
      -  Codacy
      -  Docker
      -  Support
   *  -   .. image:: https://travis-ci.org/MicroPyramid/Django-CRM.svg?branch=master
             :target: https://travis-ci.org/MicroPyramid/Django-CRM
             :alt: Travis

          .. image:: https://landscape.io/github/MicroPyramid/Django-CRM/master/landscape.svg?style=flat
             :target: https://landscape.io/github/MicroPyramid/Django-CRM/master
             :alt: Code Health

      -  .. image:: https://api.codacy.com/project/badge/Grade/b11da5f09dd542479fd3bd53944595d2
            :target: https://app.codacy.com/project/ashwin/Django-CRM/dashboard
            :alt: Codacy Dashboard
         .. image:: https://api.codacy.com/project/badge/Coverage/b11da5f09dd542479fd3bd53944595d2
            :target: https://app.codacy.com/project/ashwin/Django-CRM/dashboard
            :alt: Codacy Coverage

      -  .. image:: https://img.shields.io/docker/automated/micropyramid/django-crm.svg
            :target: https://github.com/MicroPyramid/Django-CRM
            :alt: Docker Automated
         .. image:: https://img.shields.io/docker/build/micropyramid/django-crm.svg
            :target: https://github.com/MicroPyramid/Django-CRM
            :alt: Docker Build Passing
         .. image:: https://img.shields.io/docker/stars/micropyramid/django-crm.svg
            :target: https://hub.docker.com/r/micropyramid/django-crm/
            :alt: Docker Stars
         .. image:: https://img.shields.io/docker/pulls/micropyramid/django-crm.svg
            :target: https://hub.docker.com/r/micropyramid/django-crm/
            :alt: Docker Pulls

      -  .. image:: https://badges.gitter.im/Micropyramid/Django-CRM.png
            :target: https://gitter.im/MicroPyramid/Django-CRM
            :alt: Gitter
         .. image:: https://www.codetriage.com/micropyramid/django-crm/badges/users.svg
            :target: https://www.codetriage.com/micropyramid/django-crm
            :alt: Code Helpers
         .. image:: https://img.shields.io/github/license/MicroPyramid/Django-CRM.svg
            :target: https://pypi.python.org/pypi/Django-CRM/


http://django-crm.readthedocs.io for latest documentation


This project contains the following modules.

   * Contacts
   * Accounts
   * Cases
   * Leads
   * Opportunity
   * Planner


Installation - Requirements
===========================


Ubuntu 64bit - 16.04
--------------------
$ sudo apt-get update && apt-get upgrade -y

$ sudo apt-get install -y curl wget libpq-dev python3-dev gem ruby ruby-dev build-essential libssl-dev libffi-dev python-dev python-virtualenv python-pip git redis-server libtiff5-dev libjpeg8-dev zlib1g-dev libfreetype6-dev liblcms2-dev libwebp-dev libharfbuzz-dev libfribidi-dev tcl8.6-dev tk8.6-dev python-tk

$ sudo gem install sass


If you cloned the package from git use virtualenv to install requirements::

    pip install -r requirements.txt

Visit our Django web development page [Here](https://micropyramid.com/django-ecommerce-development/)

Demo Available `here`_.

Demo credentials for Django CRM:

  * **Email:** admin@micropyramid.com
  * **Password:** admin

Feature requests and bug reports
================================
We welcome your feedback and support, raise github issue if you want to report a bug or request new feature. we are glad to help.

Need additional commercial support? `Contact us here`_

.. _contact us here: https://micropyramid.com/contact-us/

.. _here: https://django-crm.micropyramid.com/