Python Reel Theme
=================
`Python Reel Theme`_ is a free fully responsive diazo theme for Plone.

Screenshot
------------

.. image:: https://raw.github.com/quintagroup/quintagroup.theme.pythonreel/master/quintagroup/theme/pythonreel/static/images/preview.png
   :alt: Python Reel Theme Screenshot
   :align: center

Features
--------

**Responsive Web Design**

  Python Reel is a fully responsive theme that allows for easy viewing on mobile devices and tablets. The website will start to automatically resize and reposition the content to accommodate the different device screen sizes. 

**Customizable logo**

 Python Reel comes with the theme logo in a light and dark version. You can replace it with your own as you would do it in default Plone: in ZMI customize  *portal_skins -> sunburst_images -> logo.png.* Upload the logo from the folder in the theme package */quintagroup/theme/pythonreel/static/images.*

**Site Slogan**

 The theme has a slogan, displayed in the central part of the top area ``Python Reel Theme for Plone``. To change it, go to *Site Setup -> Theming -> Advanced Settings* tab. In *Parameter expressions* textarea change string value for *slogan*. 

**Top image**

 It is possible to set your own top image. For this add an image to the desirable location with the image shortname/id *topimage*. Add the image to site root and the image will be displayed everywhere on site; if added to a certain folder, the image will be displayed in this section only. 

**Top Text Color**
 
 You can change the color of the text information, displayed in the top area, including top navigation. Go to *Site Setup -> Theming -> Advanced Settings* tab. In *Parameter expressions* textarea change string value for *top* from ``default`` to ``white``.

**Improved thumbnail display view**

 To see the changes, in *Display* drop-down menu select ``Thumbnail`` view. Now each item will be displayed on the white background with slightly rounded corners with the description at the bottom that will slide up when you point on it. 

**Image carousel**

 To create image carousel, install Products.Carousel package and activate it via *Site Setup -> Add-ons*. 
  
 To add image carousel in the desired location shift to *Carousel* tab. Add a new carousel banner, publish it together with the whole Carousel Banners folder. Your carousel will be positioned above the content area. 

*Top Carousel*

 To have the carousel in the header, switch to *Carousel* tab and in *Unique Id* field type in *top-carousel*. Banner's title will be displayed instead the site slogan. It is possible to configure carousel behavior and add as many banners as needed for rotation. Also you can change the way the images are rotated by selecting one of the available options in the *Pager type* list box.

*Top Background Color*

 You can change the background color for the carousel, displayed in the top area. Go to *Site Setup -> Theming -> Advanced Settings* tab. In *Parameter expressions* textarea change string value for *top_background*.

**New Typography**
  
 Python Reel theme comes with a set of elegantly minimal Fonts:

* Arial
* Yorkville

**Configurable left/right column width** 

  Python Reel is flexible. It is easy to change the page layout by configuring columns width. Just go to *Site Setup -> Theming -> Advanced Settings* tab. In *Parameter expressions* textarea change the *columnonewidth*, *columntwowidth* parameters. Also you need to set the distance between the left/right columns and central content area by defining *columnsmargin* parameter. The parameter values are set in percents. Together they should allocate 100% including content area. By default left/right column has got 23.75%, content area - 49.1667%, columns margin – 1.6667%.

**Editable footer with Social media**

 The theme footer features social media icons for sharing information via *Facebook, Twitter, LinkedIn,  Plus, RSS feed*. To customize it and edit the information displayed in the footer, go to *ZMI ->  portal_view_customizations -> plone.footer*.

 **Note:** if you have downloaded a *zip* file you need to add the following code manually into *plone.footer* template to have social media displayed::

    <ul class="slinks">
      <li><a href="#" class="slink linked-in-link">LinkedIn</a></li>
      <li><a href="#" class="slink facebook-link">Facebook</a></li>
      <li><a href="#" class="slink twitter-link">Twitter</a></li>
      <li><a href="#" class="slink rss-link">RSS</a></li>
    </ul>


**Theme Extensions**

  Additional features can be activated:

* ``Products.Carousel``
   Adds rotating Carousel banner feature with adjusted styling.

* ``Products.ContentWellPortlets``
   Allows adding portlets in the header, footer and content area with adjusted styling.

* ``Products.PloneFormGen``
   Adds TTW Form Generator feature.

* ``quintagroup.dropdownmenu``
   Adds adjusted styling to drop-down menu.

* ``Products.LinguaPlone``
   Adds multilingual functionality and applies adjusted styling for language selectors.

* ``quintagroup.slidertemplates``
    Enhanced Responsive Views for NG Collection Portlet (Carousel, Shelf, Tabs)

* ``quintagroup.megamenu``  
    Clean and professional fully responsive Mega Menu solution for Plone. This product allows Plone website to display panel added to portal top as drop-down menu for navigation tabs.


Installation
============

See docs/INSTALL.txt file for detailed installation instructions.

Dependencies
============

* plone.app.theming

Recommended
===========
Python Reel responsive diazo Theme was tested with:

* Plone 4.3rc1
* plone.app.theming 1.1b2
* Products.Carousel 2.2.1
* Products.ContentWellPortlets 4.2.1
* Products.PloneFormGen 1.7.6
* quintagroup.dropdownmenu 1.2.11
* Products.LinguaPlone 4.1.3
* quintagroup.megamenu 1.3
* quintagroup.slidertemplates 1.0

Home Directory
==============

http://themes.quintagroup.com/product/python-reel

Authors
=======

* Serhiy Valchuk
* Olena Klos

Quintagroup: http://quintagroup.com, 2013

.. _`Python Reel Theme`: http://themes.quintagroup.com/product/python-reel
