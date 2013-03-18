Installation
------------

quintagroup.theme.pythonreel can be installed in any of the following ways. 

Installation via diazo panel
============================

* Download zip file at http://plone.org/products/pythonreel-plone-theme/releases/1.1/pythonreel.zip
* Import the theme at the 'Diazo theme' control panel

Installation via buildout
=========================

In the buildout.cfg file of your instance:

* Add ``quintagroup.theme.pythonreel`` to the list of eggs to install::

    [buildout]
    ...
    eggs =
        ...
        quintagroup.theme.pythonreel

* Re-run buildout::

    $ ./bin/buildout

* Restart the Zope server::

    $ ./bin/instance restart

Then activate 'Python Reel Theme' in Plone (Site Setup -> Add-ons).


Installation: development mode
==============================

If you want to customize Python Reel Theme please use the following installation instructions: 

* download ``quintagroup.theme.pythonreel-version.zip`` archive from http://pypi.python.org/pypi/quintagroup.theme.pythonreel
* extract theme archive to get ``quintagroup.theme.pythonreel-version`` folder. Remove version from 
  folder name to have ``quintagroup.theme.pythonreel`` folder
* put ``quintagroup.theme.pythonreel`` folder into ``src`` directory of your buildout
* in buildout.cfg file of your buildout add ``quintagroup.theme.pythonreel`` to the list of eggs you are developing and  to the list of eggs to install::

       [buildout]
       ...
       develop = src/quintagroup.theme.pythonreel
       ...
       eggs =
           ...
           quintagroup.theme.pythonreel
   
* Re-run buildout::

    $ ./bin/buildout

* Start instance in development mode::

    $ ./bin/instance fg

* Install ``Python Reel Theme`` in Plone (Site Setup -> Add-ons).

Now you can customize Python Reel Theme by modifying ``quintagroup.theme.pythonreel`` package in ``src`` directory 
of your buildout.