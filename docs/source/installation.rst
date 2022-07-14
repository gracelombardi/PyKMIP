Installation
============
Python 2.7
~~~~~~~~~~
You can install PyKMIP via ``pip``

.. code-block:: console

    $ sudo pip install pykmip

Python 3.4+
~~~~~~~~~~~
You can install PyKMIP via ``pip3``:

.. code-block:: console

    $ sudo pip3 install pykmip

Supported platforms
-------------------
PyKMIP is tested on Python 2.7, 3.4, 3.5, 3.6, and 3.7 on the following
operating systems:

* Ubuntu 12.04, 14.04, and 16.04

PyKMIP also works on Windows and MacOSX however these platforms are not
officially supported or tested.

Building PyKMIP on Linux
------------------------

Python 2.7
~~~~~~~~~~
You can install PyKMIP from source via ``git``:

.. code-block:: console

    $ sudo git clone https://github.com/openkmip/pykmip.git
    $ sudo python pykmip/setup.py install

Ubuntu
******
If you are on a fresh Linux build, you may also need several additional system
dependencies, including headers for Python, OpenSSL, ``libffi``, and
``libsqlite3``.

.. code-block:: console

    $ sudo apt-get install python-dev libffi-dev libssl-dev libsqlite3-dev


Python 3.4+
~~~~~~~~~~~
You can install PyKMIP from source via ``git``:

.. code-block:: console

    $ sudo git clone https://github.com/openkmip/pykmip.git
    $ sudo python3 pykmip/setup.py install

Ubuntu
******
If you are on a fresh Linux build, you may also need several additional system
dependencies, including headers for Python, OpenSSL, ``libffi``, and
``libsqlite3``.

.. code-block:: console

    $ sudo apt-get install python3-dev libffi-dev libssl-dev libsqlite3-dev
