RUEBOTOGIF!
==========

RUEBOTOGIF, or "[Wry Visual Commentary the ruebot Way](http://www.miskatonic.org/tmp/ruebot.html)," is a [Node](http://nodejs.org) web application that streams animated gifs from tweets from [@ruebot](http://twitter.com/ruebot).

The application is inspired by, and heavily uses the code Ed Summers wrote in the wonderful [wikitweets](https://github.com/edsu/wikitweets) application.


Thanks
------

RUEBOTOGIF stands on several giants shoulders, including:

* [express](http://expressjs.com/)
* [socket.io](http://socket.io)
* [ntwitter](https://github.com/AvianFlu/ntwitter)
* [request](https://github.com/mikeal/request)
* [unshorten](https://github.com/mathiasbynens/node-unshorten)
* [underscore](http://documentcloud.github.com/underscore/)
* [wikitweet](https://github.com/edsu/wikitweets)

Install
-------

* install node and git
* `git clone https://github.com/ruebot/ruebotogif.git`
* `cd wikistream`
* `npm install`
* `cp config.json.tmpl config.json`
* get [Twitter](https://dev.twitter.com/apps/new) credentials and add them to 
  config.json
  wikitweets can archive JSON there.
* `node app.js`
* open http://localhost:3000/ in browser

Licnse
------

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")
