Nereid for Tryton
=================

Nereid is a web framework built over Flask, with Tryton as a Backend.

Build Status (Master)
---------------------

.. image:: https://secure.travis-ci.org/openlabs/nereid.png?branch=master

`View on Travis CI <https://travis-ci.org/openlabs/nereid>`_


Build Status (Develop)
----------------------

.. image:: https://secure.travis-ci.org/openlabs/nereid.png?branch=develop

`View on Travis CI <https://travis-ci.org/openlabs/nereid>`_


Copyright
---------

Read COPYRIGHT

License
-------

GPL3 - Read LICENSE

Installation
------------

Read INSTALL

FAQ
---

What are the uses of Nereid ?
`````````````````````````````

Nereid can be used to build web applications, that could use Tryton's 
ORM as a backend. While, there are no inherent limitations which prevent
you from using nereid to build any kind of web application, the design
decision that we made while building nereid itself are tailored to build
application that extend the functionality of the ERP system, like 
e-commerce system, EDI systems, Customer/Supplier Portals etc.

Why Tryton as a backend ?
`````````````````````````

Well, why not would be our question to you ? It's scalable, it's flexible
and offers the best approach we have seen so far into a declarative coding
pattern for model design in any ORM. The unique way Tryton handles inheritance
also makes it an excellent choice. In addition to the above, Tryton by default
has several modules which make designing business applications faster in 
comparison to other frameworks.

Let's say that you want to build a customer portal, (which is our example 
application), all that you need to do from your end is create a module which
exposes the information that you want to, and leave other stuff like order
management, account management etc to the existing Tryton modules.

Which version of Tryton does nereid use ?
`````````````````````````````````````````

Nereid is available for version 2.0, 2.4, 2.6, 2.8 and 3.0.

All versions other than 3.0 are mainteinance only releases.

Now that brings us to how versioning is done

Nereid being a module for tryton, follows the same release process of Tryton
with a few differences. The repository is maintained on Github and each
version of Nereid is separately maintained on a git branch.

Specific minor releases can be identified from git tags or downloaded from
the tags page on github.

What is the license of Nereid ?
```````````````````````````````

Nereid follows the same license as that of Tryton which is GPLv3. Have a 
problem with that ? Contact us and we will be glad to help you out!

How do I install nereid ?
`````````````````````````

Just clone the module and run the python setup file. It installs all 
the dependencies too.

::

    $ git clone git://github.com/openlabs/nereid.git
    $ cd nereid
    $ python setup.py install

Is nereid modular ?
```````````````````

Depends on what you think modular is. For us we think Nereid is modular 
because you could separate logically different functionality into a 
separate Tryton module and then the functionality would be available 
to you depending on what modules are installed in the database that you
are accessing.

A little history
````````````````

The initial goal was to build an e-commerce system over OpenERP 
called Callisto, and we did! It worked, but never scaled on OpenERP.
The license sucked (surprise)! and then we saw that most issues we saw
with OpenERP don't exist in Tryton. And, we were right.

If you want to know more about why we made these design decisions, 
feel free to drop us a mail

Authors and Contributors
````````````````````````

Nereid was built at `Openlabs <http://www.openlabs.co.in>`_. It's now 
opensource, feel free to fork and contribute! Hate us! Just fork You 
can get hold of @sharoonthomas or @shalabhaggarwal if you have some 
techy questions to drill with.

Support or Contact
``````````````````

Having trouble with Nereid? Check out the documentation at TODO or 
contact sales@openlabs.co.in and we’ll help you sort it out.
