Adds a menu that dynamically generates menu links to all existing organisms on the site.

# Install

This module should be installed in the modules folder of your Drupal installation (i.e. sites/all/modules). To install the module, run the following.

`git clone https://github.com/jwest60/tripal_manage_menus.git`

To use the module, you must enable it first. This can be done through the user interface, but the suggested method is to install with drush using the following command.

`drush en tripal_manage_menus`

This will automatically create a menu link with child menu links to all the organisms that exist on your site.
