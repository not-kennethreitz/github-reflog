GitHub Reflog v1.3.21
=====================

Welcome to the first edition of The GitHub Reflog. This is a
new weekly installment chronicling awesome GitHub repos, brought to
you by `Kenneth Reitz <https://github.com/kennethreitz>`_, one of
the classy gentlemen behind
`The Changelog <http://thechangelog.com>`_ and a ton of
`open source projects <https://github.com/kennethreitz>`_.



Featured Repo of the Week
~~~~~~~~~~~~~~~~~~~~~~~~~

`devstructure/blueprint <https://github.com/devstructure/blueprint>`_
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

This is one of the coolest projects I've seen in a long time.

Simply put, Blueprint reverse engineers servers. It scans your
system, records installed packages from various managers (aptitude,
ruby's gem, python's pip, etc), archives software built from
source, and records configuration file changes. It then packages
your entire server configuration into a ``bootstrap.sh`` file with
an attached archive. You can take that bootstrap package and run it
anywhere to replicate your server setup.

Then, Blueprint takes it to the next level: it generates full
recipes/manifests for both
`Chef <https://github.com/opscode/chef>`_ and
`Puppet <https://github.com/puppetlabs/puppet>`_ with the
``blueprint-create {-C | -P}`` command.

Of course, QA is required for the resulting recipes, but it's a
definitely a great first step for streamlining your existing
systems.

Bon appétit!



Awesome Repo of the Week
~~~~~~~~~~~~~~~~~~~~~~~~

`drbrain/meme <https://github.com/drbrain/meme/>`_
++++++++++++++++++++++++++++++++++++++++++++++++++

I CAN HAS MEME? Meme is an awesome Ruby gem for generating
memegenerator.net images from the command line. It features SPARTA,
PHILOSORAPTOR, KEANU, TROLLFACE, and many more. The resulting pull
requests are definitely
`worth looking at <https://github.com/drbrain/meme/pull/13>`_.

::

    $ meme US_POINT 'I want you' 'to merge this'

.. image:: https://d3nwyuy0nl342s.cloudfront.net/img/5e625c6296a67da465ffccdb
    382e318a6af02d63/687474703a2f2f692e696d6775722e636f6d2f64527542422e6a7067



Remarkable Repos
~~~~~~~~~~~~~~~~


-  `taitems/Aristo-jQuery-UI-Theme <https://github.com/taitems/Aristo-jQuery-UI-Theme>`_:
     This is not a new project, but it received a lot of attention this
     week. Aristo is a
     `beautiful <http://taitems.github.com/Aristo-jQuery-UI-Theme/>`_
     theme for `jQuery UI <https://github.com/jquery/jquery-ui>`_ that
     emulates the elegant style of the
     `Cappuccino <https://github.com/280north/cappuccino>`_ JavaScript
     framework. jQuery UI has a bad reputation for having
     less-than-desirable themes available for its widgets. Aristo
     strives to fix that.

-  `brainsik/virtualenv-burrito <https://github.com/brainsik/virtualenv-burrito>`_:
     This project simplifies the
     `virtualenv <https://github.com/pypa/virtualenv>`_/wrapper setup in
     your Python development environment. Sprinters at last week's PyCon
     2011 had to spend a large amount of time setting up their
     environments before they could contribute. This project aims to
     remove that overhead.

-  `maccman/ichabod <https://github.com/maccman/ichabod>`_:
     This project lets you run headless WebKit JavaScript tests from the
     command line. It currently offers Jasmine and QUnit testing
     support. It also gives you an interactive JavaScript console that
     has access to the Ruby stack.



Promising Repos
~~~~~~~~~~~~~~~


-  `twitter/commons <https://github.com/twitter/commons>`_:
     Twitter's internal common libraries for the JVM. Readme and build
     instructions haven't been written yet, but this looks like an
     extensive library suite. Everything from a
     `memcached <https://github.com/memcached/memcached>`_ interface to
     an argument parser is included. Check out
     `the documentation <http://twitter.github.com/commons/apidocs/index.html>`_
     to learn more.

-  `extend/cowboy <https://github.com/extend/cowboy>`_: 
     This "Small, fast, modular HTTP server" is implemented 100% in Erlang.
     It's an ambitious project that's still in the early development
     stage. Contributors are welcome!


Feedback is appreciated! Send any questions, suggestions, and
anonymous tips to reflog@kennethreitz.com.

--------------

For more open source news, check out
`The Changelog <http://thechangelog.com>`_ and
`github/explore <http://github.com/explore>`_.
