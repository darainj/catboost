.. image:: https://img.shields.io/pypi/v/backports.functools_lru_cache.svg
   :target: `PyPI link`_

.. image:: https://img.shields.io/pypi/pyversions/backports.functools_lru_cache.svg
   :target: `PyPI link`_

.. _PyPI link: https://pypi.org/project/backports.functools_lru_cache

.. image:: https://github.com/jaraco/backports.functools_lru_cache/workflows/tests/badge.svg
   :target: https://github.com/jaraco/backports.functools_lru_cache/actions?query=workflow%3A%22tests%22
   :alt: tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. image:: https://readthedocs.org/projects/backportsfunctools_lru_cache/badge/?version=latest
   :target: https://backportsfunctools_lru_cache.readthedocs.io/en/latest/?badge=latest

.. image:: https://tidelift.com/badges/package/pypi/backports.functools_lru_cache
   :target: https://tidelift.com/subscription/pkg/pypi-backports.functools_lru_cache?utm_source=pypi-backports.functools_lru_cache&utm_medium=readme

Backport of functools.lru_cache from Python 3.3 as published at `ActiveState
<http://code.activestate.com/recipes/578078/>`_.

Usage
=====

Consider using this technique for importing the 'lru_cache' function::

    try:
        from functools import lru_cache
    except ImportError:
        from backports.functools_lru_cache import lru_cache


For Enterprise
==============

Available as part of the Tidelift Subscription.

This project and the maintainers of thousands of other packages are working with Tidelift to deliver one enterprise subscription that covers all of the open source you use.

`Learn more <https://tidelift.com/subscription/pkg/pypi-backports.functools_lru_cache?utm_source=pypi-backports.functools_lru_cache&utm_medium=referral&utm_campaign=github>`_.

Security Contact
================

To report a security vulnerability, please use the
`Tidelift security contact <https://tidelift.com/security>`_.
Tidelift will coordinate the fix and disclosure.
