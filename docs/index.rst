django-simple-history
=====================

.. image:: https://secure.travis-ci.org/treyhunner/django-simple-history.svg?branch=master
   :target: http://travis-ci.org/treyhunner/django-simple-history
   :alt: Build Status

.. image:: https://readthedocs.org/projects/django-simple-history/badge/?version=latest
   :target: https://django-simple-history.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. image:: https://img.shields.io/codecov/c/github/treyhunner/django-simple-history/master.svg
   :target: http://codecov.io/github/treyhunner/django-simple-history?branch=master
   :alt: Test Coverage

.. image:: https://img.shields.io/pypi/v/django-simple-history.svg
   :target: https://pypi.python.org/pypi/django-simple-history
   :alt: PyPI Version

.. image:: https://api.codeclimate.com/v1/badges/66cfd94e2db991f2d28a/maintainability
   :target: https://codeclimate.com/github/treyhunner/django-simple-history/maintainability
   :alt: Maintainability

.. image:: https://pepy.tech/badge/django-simple-history
   :target: https://pepy.tech/project/django-simple-history
   :alt: Downloads

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/ambv/black
   :alt: Code Style


django-simple-history stores Django model state on every create/update/delete.

This app supports the following combinations of Django and Python:

==========  =======================
  Django      Python
==========  =======================
1.11        2.7, 3.4, 3.5, 3.6, 3.7
2.0         3.4, 3.5, 3.6, 3.7
2.1         3.5, 3.6, 3.7
==========  =======================

Contribute
----------

- Issue Tracker: https://github.com/treyhunner/django-simple-history/issues
- Source Code: https://github.com/treyhunner/django-simple-history

Pull requests are welcome.


Documentation
-------------

.. toctree::
   :maxdepth: 2

   quick_start
   querying_history
   admin
   historical_model
   user_tracking
   signals
   history_diffing
   multiple_dbs
   utils
   common_issues


.. include:: ../CHANGES.rst
