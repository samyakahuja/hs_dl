HorribleSubs Downloader
=======================

Inspiration
-----------

There are a lot of anime on H.S. for which there is no batch-download
available. Purpose of this package is to implement that.

Introduction
------------

hs_dl (written in python3) takes in an anime_link that corresponds to the show
page on horrible subs for the anime you want to download torrents for.

PyPI package
------------

https://pypi.org/project/hs-dl/

Installation
------------

.. code:: shell
    
    python3 -m pip install hs_dl

Running
-------

**Basic**
.. code:: shell
    
    python hs_dl https://horriblesubs.info/shows/shingeki-no-kyojin/

**Specifying quality**
.. code:: shell
    
    python hs_dl https://horriblesubs.info/shows/shingeki-no-kyojin/ -q 720   

**Dry Mode**
.. code:: shell    
    
    python hs_dl https://horriblesubs.info/shows/shingeki-no-kyojin/ -q 720 -n

For more options try: `python hs_dl -h`

Source Code
-----------

Private for now


Todo
----

- Implement selective torrent downloading
- Implement Multiprocessing pool
- Automate torrent adding to client like qbittorent


