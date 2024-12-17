⛔️ DEPRECATED
===============

This repository is no longer supported, please consider using alternatives.

.. image:: http://unmaintained.tech/badge.svg
  :target: http://unmaintained.tech
  :alt: No Maintenance Intended

MicroPython Library for the the Temperature and Humidity SI7021 Sensor

Installing with mip
====================

To install using mpremote

.. code-block:: shell

    mpremote mip install github:jposada202020/MicroPython_SI7021

To install directly using a WIFI capable board

.. code-block:: shell

    mip.install("github:jposada202020/MicroPython_SI7021")


Installing Library Examples
============================

If you want to install library examples:

.. code-block:: shell

    mpremote mip install github:jposada202020/MicroPython_SI7021/examples.json

To install directly using a WIFI capable board

.. code-block:: shell

    mip.install("github:jposada202020/MicroPython_SI7021/examples.json")




Installation
=============

On supported GNU/Linux systems like the Raspberry Pi, you can install the driver locally `from
PyPI <https://pypi.org/project/micropython-si7021/>`_.
To install for current user:

.. code-block:: shell

    pip3 install micropython-si7021

To install system-wide (this may be required in some cases):

.. code-block:: shell

    sudo pip3 install micropython-si7021

To install in a virtual environment in your current project:

.. code-block:: shell

    mkdir project-name && cd project-name
    python3 -m venv .venv
    source .env/bin/activate
    pip3 install micropython-si7021

Documentation
=============
API documentation for this library can be found on `Read the Docs <https://micropython-si7021.readthedocs.io/>`_.
