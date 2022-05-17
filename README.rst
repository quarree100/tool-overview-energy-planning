========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        |
        | |scrutinizer| |codacy|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/tool-overview-energy-planning/badge/?style=flat
    :target: https://tool-overview-energy-planning.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/joroeder/tool-overview-energy-planning/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/joroeder/tool-overview-energy-planning/actions

.. |codacy| image:: https://img.shields.io/codacy/grade/[Get ID from https://app.codacy.com/gh/joroeder/tool-overview-energy-planning/settings].svg
    :target: https://www.codacy.com/app/joroeder/tool-overview-energy-planning
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/tool-overview-energy-planning.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/tool-overview-energy-planning

.. |wheel| image:: https://img.shields.io/pypi/wheel/tool-overview-energy-planning.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/tool-overview-energy-planning

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/tool-overview-energy-planning.svg
    :alt: Supported versions
    :target: https://pypi.org/project/tool-overview-energy-planning

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/tool-overview-energy-planning.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/tool-overview-energy-planning

.. |commits-since| image:: https://img.shields.io/github/commits-since/joroeder/tool-overview-energy-planning/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/joroeder/tool-overview-energy-planning/compare/v0.0.0...main


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/joroeder/tool-overview-energy-planning/main.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/joroeder/tool-overview-energy-planning/


.. end-badges

Overview of tools for the planning of regional and district energy systems and infrastructures

* Free software: MIT license

Installation
============

::

    pip install tool-overview-energy-planning

You can also install the in-development version with::

    pip install https://github.com/joroeder/tool-overview-energy-planning/archive/main.zip


Documentation
=============


https://tool-overview-energy-planning.readthedocs.io/


Development
===========

To run all the tests run::

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
