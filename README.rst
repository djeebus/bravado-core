.. image:: https://img.shields.io/travis/Yelp/bravado-core.svg
  :target: https://travis-ci.org/Yelp/bravado-core?branch=master

.. image:: https://img.shields.io/coveralls/Yelp/bravado-core.svg
  :target: https://coveralls.io/r/Yelp/bravado-core

.. image:: https://img.shields.io/pypi/v/bravado-core.svg
    :target: https://pypi.python.org/pypi/bravado-core/
    :alt: PyPi version

.. image:: https://img.shields.io/pypi/pyversions/bravado_core.svg
    :target: https://pypi.python.org/pypi/bravado-core/
    :alt: Supported Python versions

bravado-core
============

About
-----

bravado-core is a Python library that adds client-side and server-side support for the Swagger 2.0 Specification.

Features
--------
* Swagger schema validation
* Marshaling, transformation, and validation of requests and responses
* Models as Python classes or dicts
* Custom formats for type conversion

Documentation
-------------

More documentation is available at http://bravado-core.readthedocs.org

Installation
------------

::

    $ pip install bravado-core

Development
===========

| Code is documented using `Sphinx <http://sphinx-doc.org/>`__.
| `virtualenv <http://virtualenv.readthedocs.org/en/latest/virtualenv.html>`__ is recommended to keep dependencies and libraries isolated.
| `tox <https://tox.readthedocs.org/en/latest/>`__ is used for standardized testing.

Setup
-----

::

    # Run tests
    tox

    # Install git pre-commit hooks
    .tox/py27/bin/pre-commit install


License
-------

| Copyright (c) 2013, Digium, Inc. All rights reserved.
| Copyright (c) 2014-2015, Yelp, Inc. All rights reserved.

Bravado is licensed with a `BSD 3-Clause
License <http://opensource.org/licenses/BSD-3-Clause>`__.
