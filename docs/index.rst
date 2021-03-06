.. pinttrs documentation master file, created by
   sphinx-quickstart on Tue Jan 19 18:21:12 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

:hide-toc:

Pinttrs
=======

Pinttrs v\ |release|.

.. image:: https://img.shields.io/pypi/v/pinttrs?color=blue&style=flat-square
   :target: https://pypi.org/project/pinttrs

.. image:: https://img.shields.io/conda/v/eradiate/pinttrs?color=blue&style=flat-square
   :target: https://anaconda.org/eradiate/pinttrs

.. image:: https://img.shields.io/github/workflow/status/leroyvn/pinttrs/Tests/main?style=flat-square
   :target: https://github.com/leroyvn/pinttrs/actions/workflows/tests.yml

.. image:: https://codecov.io/gh/leroyvn/pinttrs/branch/main/graph/badge.svg?style=flat-square
   :target: https://codecov.io/gh/leroyvn/pinttrs

.. image:: https://img.shields.io/readthedocs/pinttrs?style=flat-square
   :target: https://pinttrs.readthedocs.io

.. image:: https://img.shields.io/badge/code%20style-black-black?style=flat-square
   :target: https://github.com/psf/black

.. image:: https://img.shields.io/badge/%20imports-isort-blue?style=flat-square&labelColor=orange
   :target: https://pycqa.github.io/isort

*Pint meets attrs.*

Pinttrs provides tools to bring extra functionality to your |attrs|_ classes
using Pint_.

.. |attrs| replace:: ``attrs``
.. _attrs: https://www.attrs.org/
.. _Pint: https://pint.readthedocs.io/

Motivation
----------

The amazing attrs_ library is a game-changer when it comes to writing classes.
Its initialisation sequence notably allows for automated conversion and
verification of attribute values. This package is an attempt at designing a
system to apply units automatically and reliably to attributes with Pint_.

Features
--------

- :ref:`Attach automatically units to unitless values passed to initialise an attribute <usage-attach_units>`
- :ref:`Verify unit compatibility when assigning a value to an attribute <usage-attach_units-validators_converters>`
- :ref:`Interpret units in dictionaries with a simple syntax <usage-interpret_dicts>`
- :ref:`Define unit context to vary unitless value interpretation dynamically <usage-unit_contexts>`

Getting started
---------------

Install from PyPI in your virtual environment:

.. code-block:: bash

   python -m pip install pinttrs

Using Conda:

.. code-block:: bash

   conda install -c eradiate pinttrs -c conda-forge

The :ref:`usage` section presents Pinttrs's features and how to use them.

License
-------

Pinttrs is distributed under the terms of the
`MIT license <https://choosealicense.com/licenses/mit/>`_.

About
-----

Pinttrs is written and maintained by `Vincent Leroy <https://github.com/leroyvn>`_.

Development is supported by `Rayference <https://www.rayference.eu>`_.

Pinttrs is a component of the
`Eradiate radiative transfer model <https://www.eradiate.eu>`_.

The Pinttrs logo is based on
`Agus Nugroho <https://www.iconfinder.com/nugrohoagus>`_'s glass icon and parts of
the ``attrs`` logo.

.. toctree::
   :hidden:

   rst/usage
   rst/compatible

.. toctree::
   :caption: Development
   :hidden:

   rst/dev
   rst/api
   rst/changes
   GitHub repository <https://github.com/leroyvn/pinttrs>
