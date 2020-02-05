========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/zeekoers/badge/?style=flat
    :target: https://readthedocs.org/projects/zeekoers
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/toolunious/zeekoers.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/toolunious/zeekoers

.. |codecov| image:: https://codecov.io/github/toolunious/zeekoers/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/toolunious/zeekoers

.. |version| image:: https://img.shields.io/pypi/v/zeekoers.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/zeekoers

.. |wheel| image:: https://img.shields.io/pypi/wheel/zeekoers.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/zeekoers

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/zeekoers.svg
    :alt: Supported versions
    :target: https://pypi.org/project/zeekoers

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/zeekoers.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/zeekoers

.. |commits-since| image:: https://img.shields.io/github/commits-since/toolunious/zeekoers/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/toolunious/zeekoers/compare/v0.0.0...master



.. end-badges

Zeekoers, a library for CQRS in python

* Free software: Apache Software License 2.0

Installation
============

::

    pip install zeekoers

You can also install the in-development version with::

    pip install https://github.com/toolunious/zeekoers/archive/master.zip


Documentation
=============


https://zeekoers.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
