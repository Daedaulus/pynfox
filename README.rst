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
        | |codecov|
        | |codacy|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/pynfox/badge/?style=flat
    :target: https://readthedocs.org/projects/pynfox
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/Labrys/pynfox.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/Labrys/pynfox

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/Labrys/pynfox?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/Labrys/pynfox

.. |requires| image:: https://requires.io/github/Labrys/pynfox/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/Labrys/pynfox/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/Labrys/pynfox/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Labrys/pynfox

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/Labrys/pynfox
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/pynfox.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/pynfox

.. |commits-since| image:: https://img.shields.io/github/commits-since/Labrys/pynfox/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Labrys/pynfox/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pynfox.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/pynfox

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pynfox.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/pynfox

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pynfox.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/pynfox


.. end-badges

A media information tool.

* Free software: BSD license

Installation
============

::

    pip install pynfox

Documentation
=============

https://pynfox.readthedocs.io/

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
