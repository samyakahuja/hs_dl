Quickstart
==========

hs_dl is written in python3.6 so make sure that running the code below
results in version above 3.6

.. code:: shell
    
    python --version

Note: This guide assumes that `python` is linked to `python3` in your system.

Installation
------------

.. code:: shell
    
    python -m pip install hs_dl

Running
-------

**Basic**

.. code:: shell
   
    python -m hs_dl https://horriblesubs.info/shows/shingeki-no-kyojin/

**Specifying quality**

.. code:: shell
    
    python -m hs_dl https://horriblesubs.info/shows/shingeki-no-kyojin/ -q 720   

**Dry Mode**

.. code:: shell    
    
    python -m hs_dl -q 720 -n https://horriblesubs.info/shows/shingeki-no-kyojin/

**Special Characters**

It may be the case that your link contains special characters and your shell
isn't able to handle it. So in that case put anime_link in single quotes.

.. code:: shell    
    
    python -m hs_dl 'https://horriblesubs.info/shows/shingeki-no-kyojin/#21'

For more options try: 

.. code:: shell
    
    python -m hs_dl -h


Answers to FAQ
--------------

- hs_dl is short for HorribleSubs Downloader.
- As of yet you can only download torrents for entire show.
- Yeah I know its kinda slow! (‾ʖ̫‾)

