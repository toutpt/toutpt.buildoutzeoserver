Introduction
============

This buildout provides a zeoserver for your project with backup support.

The database doesn't need all the project related code, this is why we deploy
zeoserver outside of the project.

How to use
==========

configure your environement by copy/paste buildout.cfg.in to buildout.cfg::

  cp buildout.cfg.in buildout.cfg
  vim buildout.cfg

bootstrap::

  python bootstrap.py
  bin/buildout

Version supported:

* buildout-2.13.15.cfg for zope2.13.15 database (used by Plone 4.1)
* buildout-2.13.16.cfg for zope2.13.16 database (used by Plone 4.2)


Credits
=======

Companies
---------

|makinacom|_

* `Planet Makina Corpus <http://www.makina-corpus.org>`_
* `Contact Makina Corpus <mailto:python@makina-corpus.org>`_

Authors
-------

- JeanMichel FRANCOIS aka toutpt <toutpt@gmail.com>

.. Contributors
.. ------------

.. |makinacom| image:: http://depot.makina-corpus.org/public/logo.gif
.. _makinacom:  http://www.makina-corpus.com

