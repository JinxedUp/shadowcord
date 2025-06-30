Shadowcord
==========

.. image:: https://img.shields.io/pypi/v/Shadowcord.svg
   :target: https://pypi.org/project/Shadowcord/
   :alt: PyPI version info
.. image:: https://img.shields.io/pypi/pyversions/Shadowcord.svg
   :target: https://pypi.org/project/Shadowcord/
   :alt: PyPI supported Python versions

A selfbot fork of discord.py version 1.7.3, optimized for selfbot usage.

Installation
------------

Requires Python 3.8+

To install:

.. code:: sh

    pip install -U Shadowcord


-----

Same API as discord.py 1.7.3, you can use existing discord.py examples.


```rst
.. code-block:: python

    import discord

    client = discord.Client()

    @client.event
    async def on_ready():
        print(f"Logged in as {client.user}")

    client.run('token')
