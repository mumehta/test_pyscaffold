.. These are examples of badges you might want to add to your README:
   please update the URLs accordingly

    .. image:: https://api.cirrus-ci.com/github/<USER>/test_pyscaffold.svg?branch=main
        :alt: Built Status
        :target: https://cirrus-ci.com/github/<USER>/test_pyscaffold
    .. image:: https://readthedocs.org/projects/test_pyscaffold/badge/?version=latest
        :alt: ReadTheDocs
        :target: https://test_pyscaffold.readthedocs.io/en/stable/
    .. image:: https://img.shields.io/coveralls/github/<USER>/test_pyscaffold/main.svg
        :alt: Coveralls
        :target: https://coveralls.io/r/<USER>/test_pyscaffold
    .. image:: https://img.shields.io/pypi/v/test_pyscaffold.svg
        :alt: PyPI-Server
        :target: https://pypi.org/project/test_pyscaffold/
    .. image:: https://img.shields.io/conda/vn/conda-forge/test_pyscaffold.svg
        :alt: Conda-Forge
        :target: https://anaconda.org/conda-forge/test_pyscaffold
    .. image:: https://pepy.tech/badge/test_pyscaffold/month
        :alt: Monthly Downloads
        :target: https://pepy.tech/project/test_pyscaffold
    .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
        :alt: Twitter
        :target: https://twitter.com/test_pyscaffold

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

===============
test_pyscaffold
===============


    Add a short description here!


A longer description of your project goes here...


.. _pyscaffold-notes:

Making Changes & Contributing
=============================

This project uses `pre-commit`_, please make sure to install it before making any
changes::

    pip install pre-commit
    cd test_pyscaffold
    pre-commit install

It is a good idea to update the hooks to the latest version::

    pre-commit autoupdate

Don't forget to tell your contributors to also install and use pre-commit.

.. _pre-commit: https://pre-commit.com/

Note
====

This project has been set up using PyScaffold 4.3.1. For details and usage
information on PyScaffold see https://pyscaffold.org/.


How did i created this project worked on my system
===================================================

Ref:
https://asciinema.org/a/qzh5ZYKl1q5xYEnM4CHT04HdW?autoplay=1
https://pypi.org/project/PyScaffold/

system pre requisites:

1. should have `virtualenv`, `virtualenvwrapper`, `pyscaffold`, `tox` and `pre-commit` installed.
2. mkvirtualenv `test_pyscaffold`
3. putup -i `test_pyscaffold`
4. Update properties:
    description, url, pre-commit, virtualenv venv, cirrus (if using as ci), verbose (optional)
5. cd `test_pyscaffold`
6. setvirtualenv
7. tox -av
8. tox
9. git tag v0.0.1
10. tox -e build
