websockets
==========

|pypi-v| |pypi-pyversions| |pypi-l| |pypi-wheel| |tests|

.. |pypi-v| image:: https://img.shields.io/pypi/v/websockets.svg
    :target: https://pypi.python.org/pypi/websockets

.. |pypi-pyversions| image:: https://img.shields.io/pypi/pyversions/websockets.svg
    :target: https://pypi.python.org/pypi/websockets

.. |pypi-l| image:: https://img.shields.io/pypi/l/websockets.svg
    :target: https://pypi.python.org/pypi/websockets

.. |pypi-wheel| image:: https://img.shields.io/pypi/wheel/websockets.svg
    :target: https://pypi.python.org/pypi/websockets

.. |tests| image:: https://github.com/aaugustin/websockets/actions/workflows/tests.yml/badge.svg
   :target: https://github.com/aaugustin/websockets/actions/workflows/tests.yml

``websockets`` is a library for building WebSocket servers_ and clients_ in
Python with a focus on correctness and simplicity.

.. _servers: https://github.com/aaugustin/websockets/blob/master/example/server.py
.. _clients: https://github.com/aaugustin/websockets/blob/master/example/client.py

Built on top of :mod:`asyncio`, Python's standard asynchronous I/O framework,
it provides an elegant coroutine-based API.

Here's how a client sends and receives messages:

.. literalinclude:: ../example/hello.py

And here's an echo server:

.. literalinclude:: ../example/echo.py

Do you like it? Let's dive in!

Tutorials
---------

If you're new to ``websockets``, this is the place to start.

.. toctree::
   :maxdepth: 2

   intro
   faq

How-to guides
-------------

These guides will help you build and deploy a ``websockets`` application.

.. toctree::
   :maxdepth: 2

   cheatsheet
   deployment
   extensions
   howto/django
   heroku

Reference
---------

Find all the details you could ask for, and then some.

.. toctree::
   :maxdepth: 2

   api/index

Discussions
-----------

Get a deeper understanding of how ``websockets`` is built and why.

.. toctree::
   :maxdepth: 2

   design
   limitations
   security

Project
-------

This is about websockets-the-project rather than websockets-the-software.

.. toctree::
   :maxdepth: 2

   changelog
   contributing
   license
   For enterprise <tidelift>
