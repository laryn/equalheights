
Drupal equalheights.module README.txt
==============================================================================

This module implements a jQuery plugin that can equalize the height of the
user specified elements with the same class.
By default, the height of the tallest element is used, but minimum and
maximum height can also be set.
The format for the admin settings should be '.classname:minheight,maxheight'.
To find out more about the plugin, go to
http://www.cssnewbie.com/equalheights-jquery-plugin/

Installation
------------

Before installing equalheights module, download imagesloaded plugin from https://github.com/desandro/imagesloaded.
You need two files: jquery.imagesloaded.js and jquery.imagesloaded.min.js. They should be copied to sites/all/libraries/imagesloaded.
You can also use git to clone the repository from the github.

Copy the module to the directory where you store contributed modules and enable
it on the admin modules page. Go to admin/config/development/equalheights and
add the classes for the elements that should have the same height (optionally,
add minimum and maximum height as well as overflow).

Author of the jQuery plugin
--------------------
Rob Glazebrook
http://www.cssnewbie.com/equalheights-jquery-plugin/

Author of the module
--------------------
Drupal librarian
transgarret@gmail.com