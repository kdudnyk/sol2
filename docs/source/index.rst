.. sol documentation master file, created by
   sphinx-quickstart on Mon Feb 29 21:49:51 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. image:: media/sol.png
	:target: https://github.com/ThePhD/sol2
	:alt: sol repository
	:align: center

sol |version|
=============
*a fast, simple C++ and Lua Binding*


When you need to hit the ground running with Lua and C++, `sol`_ is the go-to framework for high-performance binding with an easy to use API.

get going:
----------

.. toctree::
	:maxdepth: 1
	:name: mastertoc
	
	tutorial/all-the-things
	tutorial/tutorial-top
	errors
	compilation
	features
	functions
	usertypes
	containers
	threading
	traits
	api/api-top
	mentions
	benchmarks
	performance
	safety
	exceptions
	rtti
	codecvt
	build
	licenses
	origin


connect
--------

Come to the Github Issues or the Discord! We've got a friendly community, and they can help you out or you can come just to talk about the things you are working on!

|ds| |gh|


support
-------

You can support the project and other related endeavors in various ways.

|pa| |kf| |lp| |pp|  


You can support sol3 development by using any of the above. This is a time-consuming effort, so individuals who donate get to:

- steer the direction and time spent on sol
- get a role on the Discord server
- get their name put up in the CONTRIBUTORS list
- put something of their choice on sol3's README or the documentation's front page

You can also help out the library by submitting pull requests to fix anything or add anything you think would be helpful! This includes making small, useful examples of something you haven't seen, or fixing typos and bad code in the documentation.


"I need feature X, maybe you have it?"
--------------------------------------
Take a look at the :doc:`Features<features>` page: it links to much of the API. You can also just straight up browse the :doc:`api<api/api-top>` or ease in with the :doc:`tutorials<tutorial/tutorial-top>`. To know more about the implementation for usertypes, see :doc:`here<usertypes>` To know how function arguments are handled, see :ref:`this note<function-argument-handling>`. Don't see a feature you want? Send inquiries for support for a particular abstraction to the `issues`_ tracker.


the basics:
-----------

.. note::
	The code below *and* more examples can be found in the `examples directory`_.


.. literalinclude:: ../../examples/source/docs/simple_functions.cpp
	:name: simple-functions-example
	:linenos:

.. literalinclude:: ../../examples/source/docs/simple_structs.cpp
	:name: simple-structs-example
	:linenos:


Search
======

* :ref:`search`

.. _Sol: https://github.com/ThePhD/sol2
.. _issues: https://github.com/ThePhD/sol2/issues
.. _examples directory: https://github.com/ThePhD/sol2/tree/develop/examples

.. |pa| image:: media/become_a_patron_button.png
	:height: 50
	:target: https://www.patreon.com/thephd
	:alt: sol3 Patreon
	:align: middle
	
.. |kf| image:: media/Ko-fi_Blue.png
	:height: 50
	:target: https://ko-fi.com/thephd
	:alt: sol3 ko-fi
	:align: middle
	
.. |lp| image:: media/liberapay_logo.png
	:height: 50
	:target: https://liberapay.com/ThePhD/
	:alt: sol3 ko-fi
	:align: middle

.. |pp| image:: media/pp_cc_mark_111x69.jpg
	:height: 50
	:target: https://www.paypal.me/LMeneide
	:alt: sol3 PayPal
	:align: middle

.. |ds| image:: media/discord_logo_wordmark.png
	:height: 75
	:target: https://discord.gg/buxkYNT
	:alt: sol3 Discord

.. |gh| image:: media/github_logo.png
	:height: 75
	:target: https://github.com/ThePhD/sol2/issues
	:alt: sol3 Github Issues Page
