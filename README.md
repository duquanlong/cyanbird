Cyanbird
========
Cyanbird is a mythical bird in the book *Classic of Mountains and Seas*. It's the messenger of happiness.  
It is aslo a microframework written in Python.  
![Travis CI](https://travis-ci.org/zhaov/cyanbird.png?branch=master)

Examples
--------
    from cyanbird import GET, response, run

    @GET("/")
    def index(request):
        return response("Hello Cyanbird!")

    run()

Installation
------------

Documentation
------------

TODO
----
It is still under development. Please join me.

* delete, put, head
* template
* upload file
* cache
* some other adapters
* ajax

Thanks
------
[Ring](https://github.com/ring-clojure/ring)  
[wheezy.http](https://bitbucket.org/akorn/wheezy.http)  
[itty](https://github.com/toastdriven/itty)  
[Colubrid](http://wsgiarea.pocoo.org/colubrid/downloads/)  
[CherryPy](https://bitbucket.org/cherrypy/cherrypy/wiki/Home)  
[Django](https://github.com/django/django)  
[getting-started-with-wsgi](http://lucumr.pocoo.org/2007/5/21/getting-started-with-wsgi/)  
Some great ideas and codes may come from them.

License
-------
Copyright © 2014 Zhao Wei and released under an MIT license.
