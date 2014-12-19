
YTS
========

YTS is a python package that allows you to download movie torretns from web.It is also a python
binding for the official movie torrents YTS.

Look how easy it is to use:

    from yts import YTS
    # Get your stuff done
    y = YTS()
    y.torrents() #Lists all the latest movie torrents available.select movieID from it
    y.download(6581) #6581 is movie ID which is listed by torrents method above


That's it.Your default torrent client will be opened and torrent will be added to it.

Features
--------
- Download movies with single method
- Download latest torrents
- Search and dowload torrents
- Query the information of interested movie
- Chose movies with quality,ratings,name,date added etc.
- Redirect torrent to your favorite torrent client
- 100% authentic torrents

Installation
------------

Install $project by running:

    $ sudo pip install yts

    	or

    $ pip install yts (for windows)

Contribute
----------

- Source Code: https://github.com/narenaryan/yts

Support
-------

If you are having issues, please let us know.
You can mail me at: narenarya@live.com

License
-------

The project is licensed under the MIT license.

Documentation
-------------
Full documentation :  http://narenaryan.github.io/yts

