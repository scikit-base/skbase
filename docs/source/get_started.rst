.. _getting_started:

===========
Get Started
===========

The following information is designed to get users up and running with
``baseobject`` quickly. For more detailed information, see the links in each
of the subsections.

Installation
============

``baseobject`` currently supports:

* environments with python version 3.7, 3.8, 3.9 or 3.10
* operating systems Mac OS X, Unix-like OS, Windows 8.1 and higher
* installation via ``PyPi``

To install ``baseobject`` with its core dependencies via ``pip`` use:

.. code-block:: bash

    pip install baseobject

To install ``baseobject`` with maximum dependencies, including soft dependencies,
install with the ``all_extras`` modifier:

.. code-block:: bash

    pip install baseobject[all_extras]

For additional details see our :ref:`full installation guide <full_install>`.


Key Concepts
============

``baseobject`` seeks to provide a general :term:`framework`  for creating and
working with classes that follow `scikit-learn`_, `sktime`_ style design patterns.

Primary functionality is provided through base classes that provide interfaces for:

 - `scikit-learn`_ style parameter getting and setting
 - using :term:`tags <tag>` to record characteristics of the class that can
   be used to alter the classes code or how it interacts with other functionality
 - generating test instances

To make it easy to build :term:`toolboxes <toolbox>` and
:term:`applications <application>` that use ``baseobject's``, interfaces
are also provided for:

- retrieving information on ``baseobjects``
- testing ``baseobjects``

.. warning::

    The ``baseobject`` package is new and its interfaces are still experimental.

Quickstart
==========
The code snippets below are designed to introduce ``baseobject's``
functionality. For more detailed information see the :ref:`tutorials`,
:ref:`user_guide` and :ref:`api_ref` in ``baseobject's``
:ref:`user_documentation`.

.. _scikit-learn: https://scikit-learn.org/stable/index.html
.. _sktime: https://www.sktime.org/en/stable/index.html