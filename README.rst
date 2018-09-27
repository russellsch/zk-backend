========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/zk-backend/badge/?style=flat
    :target: https://readthedocs.org/projects/zk-backend
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/russellsch/zk-backend.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/russellsch/zk-backend

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/russellsch/zk-backend?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/russellsch/zk-backend

.. |requires| image:: https://requires.io/github/russellsch/zk-backend/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/russellsch/zk-backend/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/russellsch/zk-backend/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/russellsch/zk-backend

.. |codecov| image:: https://codecov.io/github/russellsch/zk-backend/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/russellsch/zk-backend

.. |landscape| image:: https://landscape.io/github/russellsch/zk-backend/master/landscape.svg?style=flat
    :target: https://landscape.io/github/russellsch/zk-backend/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/russellsch/zk-backend
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/russellsch/zk-backend/badges/gpa.svg
   :target: https://codeclimate.com/github/russellsch/zk-backend
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/zkbackend.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/zkbackend

.. |commits-since| image:: https://img.shields.io/github/commits-since/russellsch/zk-backend/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/russellsch/zk-backend/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/zkbackend.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/zkbackend

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/zkbackend.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/zkbackend

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/zkbackend.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/zkbackend

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/russellsch/zk-backend/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/russellsch/zk-backend/


.. end-badges

Zettelkasten Note Taking UI Backend Library

* Free software: BSD 3-Clause License

Installation
============

::

    pip install zkbackend

Documentation
=============

https://zk-backend.readthedocs.io/

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
