# Steam Gameserver Status
WordPress plugin that allows displaying the status of Steam gameservers on your blog

# Installation
1. Clone the repository to your computer
2. Unpack the archive
3. Upload the contents of the unpacked archive to /path/to/wordpress/wp-content/plugins/ in its own folder
... *Example: /var/www/wordpress/wp-content/plugins/steam-gameserver-status*
4. Login to your WordPress admin panel
5. Navigate to "Plugins" and activate the steam-gameserver-status plugin

# Configuration
Out of the box, Steam Gameserver Status comes with a bunch of configuration options. Under "Gameservers" in your WordPress admin panel you can find settings. Each option has a short description. Later on I will write a Wiki on GitHub.

# Usage
After you've added your gameservers to WordPress you will find shortcodes behind every gameserver under "Gameservers". Make sure you have enabled all the gameservers you wish to use and display on your blog. Simply copy the shortcode and paste it on a page or inside a post to display the gameserver's status. To add a gameserver to your sidebars, simply go to widgets and add it to your sidebar.

# Credits
* PHP-Source-Query
  Steam Gameserver Status relies on the library provided by xPaw, check it out here: [https://github.com/xPaw/PHP-Source-Query/](https://github.com/xPaw/PHP-Source-Query/)
* Chartist
  For graphs we used Chartist which is an amazing and easy-to-use library to generate charts. Check it out here:  [https://gionkunz.github.io/chartist-js/](https://gionkunz.github.io/chartist-js/)
