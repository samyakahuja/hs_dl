HorribleSubs Downloader
=======================

Inspiration
-----------

There are a lot of anime on H.S. for which there is no batch-download
available. Purpose of this repo is to correct that.

Introduction
------------

hs_dl takes in a anime_link that corresponds to the show page on horrible subs
for the anime you want to downlaod torrents for.

Examples
--------

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

Todo
----

- Implement selective torrent downloading
- Implement Multiprocessing pool
- Automate torrent adding to client like qbittorent


