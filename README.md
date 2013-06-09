PulsestormLauncher
==================

The fastest way to browse your Magento admin interface. 

###Description

The Pulse storm launcher provides the Magento admin console with a Quicksilver like plugin for immediate access to Magento navigation items, system configuration sections, and the Magento global search.

Original Post: http://alanstorm.com/magento_admin_navigation_launcher

###Build Instructions

The `build_launcher.bash` file is a bash script that will create a simple tar archive of the extension files. 

    $ ./build_launcher.bash
    
This script assumes the existence of a `var` folder.    

The `magento-tar-to-connect.launcher.php` file is a configuration file for the <a href="https://github.com/astorm/MagentoTarToConnect/">MagentoTarToConnect</a> command-line script.  This will allow you to build a Magento Connect 2.0 extension with the following.

    $ magento-tar-to-connect.phar magento-tar-to-connect.launcher.php
    
See the <a href="https://github.com/astorm/MagentoTarToConnect/#readme">MagentoTarToConnect README.md</a> for more information on how this tool works.     