Pylama_pylint
#############

pylama-pylint -- Support Pylint_ in Pylama_.

.. image:: http://img.shields.io/travis/cemsbr/pylama_pylint.svg?style=flat-square
    :target: http://travis-ci.org/cemsbr/pylama_pylint
    :alt: Build Status

.. contents::


Fork Considerations
===================

This fork uses the latest pylint, fix an important speed issue and other minor
bugs. If you want to use this fork instead of the official pypi package, run::

    pip uninstall pylama_pylint
    pip install git+git://github.com/cemsbr/pylama_pylint.git@master

Alternatively, you can use a commit SHA instead of *master* and/or add
``git+git...`` to a requirements file.

The other README sections are unaltered.


Requirements
=============

- python >= 2.7


Installation
============

**Pylama_pylint** should be installed using pip: ::

    pip install pylama-pylint


Usage
=====
::

    pylama -l pylint,pep8

See pylama docs for configure pylint with pylama.


Bug tracker
===========

If you have any suggestions, bug reports or
annoyances please report them to the issue tracker
at https://github.com/klen/pylama_pylint/issues


Contributing
============

Development of starter happens at github: https://github.com/klen/pylama_pylint


Contributors
============

* klen_ (horneds@gmail.com)

* Serg Baburin (https://github.com/gmist)


License
=======

Licensed under a `BSD license`_.


.. _BSD license: http://www.linfo.org/bsdlicense.html
.. _klen: http://klen.github.io
.. _Pylint: http://pylint.org
.. _Pylama: http://pylama.readthedocs.com
