GitHub Reflog v1.4.12
=====================

Welcome to the fourth edition of **The GitHub Reflog** — the weekly
chronicle of remarkable GitHub repos and community activity. For
previous editions, check out
`The Reflog Archive <https://github.com/kennethreitz/github-reflog>`_.

Featured Repo of the Week
~~~~~~~~~~~~~~~~~~~~~~~~~

`apenwarr/sshuttle <https://github.com/apenwarr/sshuttle>`_

This nifty project got quite a bit of press this week, and has
already become indispensable part of my toolkit. Sshuttle calls
itself a "Poor Man's VPN". It allows you to connect to a remote
machine as a non-privileged user and forward every port on its
network to your local machine. Once enabled, all traffic is being
routed through the server. If the server has network access to
machines that your machine cannot, you can now access those boxes
as if they were on your local network.

Port forwarding with OpenSSH is hardly new, but sshuttle forwards
*all* ports instead of only ones you specify. The only dependency
on the server is OpenSSH itself.

Liftoff!

Awesome Repo of the Week
~~~~~~~~~~~~~~~~~~~~~~~~

`asarazan/Narwhalingus-EP <https://github.com/asarazan/Narwhalingus-EP>`_

@asarazan found a great new use for GitHub this week. His band, The
Bristol 7's, decided to
`publish their EP <http://thebristol7s.wordpress.com/2011/04/10/fork-us-on-github/>`_
under the Creative Commons license. In the spirit of open source,
he decided to put it up on GitHub!

The repo includes final mixes as well as the individual audio
tracks for remixing. Pull requests welcome!

Remarkable Repos
~~~~~~~~~~~~~~~~


-  `jonromero/music-as-data <https://github.com/jonromero/music-as-data>`_:
   This Clojure project offers a live programming environment for
   generating music sequences. It allows you to treat the sequences as
   data and apply transformations to them in live environments. Check
   out the `project page <http://mad.emotionull.com/>`_ to learn
   more.

-  `37signals/pow <https://github.com/37signals/pow>`_: This
   new project from 37 Signals is a zero-config development server for
   Rack applications. Once you run its super simple installer, go to
   ``~/.pow`` and make a symlink to your app's directory. And, that's
   it! The app is now available locally at ``http://appname.dev``.

-  `DanielWaterworth/raphters <https://github.com/DanielWaterworth/raphters>`_:
   This new framework is for developing web applications in C. Yes,
   you read correctly. If you're a C aficionado that has always
   dreamed of building a modern webapp in your favorite language,
   Raphters is a great place to start. It provides a simple API for
   handling cookies, sessions, and templates. The resulting
   applications can be deployed with FastCGI.


Promising Repos
~~~~~~~~~~~~~~~


-  `cldwalker/tux <https://github.com/cldwalker/tux>`_: Tux is
   a Ruby shell interface for Sinatra. It gives you a simple interface
   to interact with all parts of your application from the
   commandline. It can directly call your helpers and views, or
   generate your own request/response data.

-  `ded/Ender.js <https://github.com/ded/Ender.js>`_: This new
   JavaScript module is actually 8 minimal utilities smashed into one:
   `klass <https://github.com/ded/klass>`_,
   `qwery <https://github.com/ded/qwery>`_,
   `bonzo <https://github.com/ded/bonzo>`_,
   `bean <https://github.com/fat/bean>`_,
   `script.js <https://github.com/ded/script.js>`_,
   `reqwest <https://github.com/ded/Reqwest>`_,
   `emile <https://github.com/ded/emile>`_, and
   `underscore.js <https://github.com/documentcloud/underscore/>`_.
   Running in at only 8KB, Ender.js combines the of all of these
   powerful modules into one elegant API. Features include: a class
   system, custom selector engine, DOM manipulation, events system,
   asynchronous dependency loading, simple animations, and a robust
   extension API. The codebase is powered by git-submodules and can be
   rebuilt with Node.js.


Feedback is appreciated! Send any questions, suggestions, and
anonymous tips to reflog@kennethreitz.com.

--------------

For more open source news, check out
`The Changelog <http://thechangelog.com>`_ and
`github.com/explore <http://github.com/explore>`_.
