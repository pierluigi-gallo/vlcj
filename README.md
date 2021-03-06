![vlcj](https://github.com/caprica/vlcj/raw/master/etc/vlcj-logo.png "vlcj")

vlcj
====

The vlcj project provides a Java framework to allow an instance of a native
[vlc](http://www.videolan.org/vlc "vlc") media player to be embedded in a Java 
AWT Window or Swing JFrame. 

You get more than just simple bindings, you also get a higher level framework
that hides a lot of the complexities of working with libvlc.

vlcj works just fine on Linux and Windows and should work on Mac - but for Mac
you likely need a bleeding-edge release of vlc.

At least JDK 1.6 is required, and it works without changes on JDK 1.7.

This is the open source vlcj project page, see also the 'official' 
[home page](http://www.capricasoftware.co.uk/vlcj "Official vlcj home page at Caprica Software")
where you can find more information as well as some new simple tutorials.

News
----

15/11/2012 [New commercial license promotion](http://goo.gl/615h1).

27/10/2012 New pre-release snapshot version 2.2.0:

* new native log integration (libvlc 2.1.x);
* new mini-framework to help make it easy to use media players in a synchronous way;
* native media discoverer integration - it is now possible to get a list of audio and video (on Linux) capture devices;
* media meta data now provides media length (if available);
* minor bug fixes and memory leak fixes.

Note: vlcj now *requires* JNA 3.5.0 or later.

20/05/2012 Released version 2.1.0, for use with libvlc 2.0.

28/01/2012 Moved to github.

You can also follow @capricasoftware on Twitter for more vlcj news.

There is also a new vlcj-users discussion group at [vlcj-users](https://groups.google.com/forum/#!forum/vlcj-users).

Documentation
-------------

The vlcj project page is at [github](http://caprica.github.com/vlcj "vlcj at github").

Online Javadoc is available:

* [2.1.0 (current)](http://caprica.github.com/vlcj/javadoc/2.1.0/index.html "2.1.0 Javadoc")
* [2.0.0](http://caprica.github.com/vlcj/javadoc/2.0.0/index.html "2.0.0 Javadoc")

Documentation is being made available at [Caprica Software](http://www.capricasoftware.co.uk/wiki "Caprica Software WIKI"). 

Support
-------

Support for commercial projects is provided exclusively on commercial terms -
send an email to the following address for more information:

> mark [dot] lee [at] capricasoftware [dot] co [dot] uk

License
-------

The vlcj framework is provided under the GPL, version 3 or later.

If you want to consider a commercial license for vlcj that allows you to use and 
redistribute vlcj without complying with the GPL then send your proposal to:

> mark [dot] lee [at] capricasoftware [dot] co [dot] uk
