===============================
setup_test
===============================

.. image:: https://img.shields.io/pypi/v/setup_test.svg
        :target: https://pypi.python.org/pypi/setup_test

.. image:: https://img.shields.io/travis/slogan621/setup_test.svg
        :target: https://travis-ci.org/slogan621/setup_test

.. image:: https://readthedocs.org/projects/setup_test/badge/?version=latest
        :target: https://readthedocs.org/projects/setup_test/?badge=latest
        :alt: Documentation Status


Python Boilerplate contains all the boilerplate you need to create a Python package.

* Free software: ISC license
* Documentation: https://setup_test.readthedocs.org.

Features
--------

* TODO

Credits
---------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Installing on Centos 6
----------------------

Some prep:

::
    $ sudo yum -y update
    $ sudo yum install epel-release
    $ sudo yum install python-pip python-wheel
    $ sudo yum install git

(above is only done once, if needed)

The actual install is 3 lines:

::
    $ git clone https://github.com/slogan621/setup_test.git
    $ cd setup_test
    $ sudo python setup.py install

(lots of output here)

Check that the install was performed:

::
    $ ls /usr/local/lib
    donothing.so 
    $ python
    Python 2.6.6 (r266:84292, Jul 23 2015, 15:22:56) 
    [GCC 4.4.7 20120313 (Red Hat 4.4.7-11)] on linux2
    Type "help", "copyright", "credits" or "license" for more information.
    >>> import setup_test
    >>> print setup_test
    <module 'setup_test' from
    '/usr/lib/python2.6/site-packages/setup_test-0.1.0-py2.6.egg/setup_test/__init__.pyc'>

