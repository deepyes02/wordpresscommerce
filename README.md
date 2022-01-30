**WooCommerce Project**

***Dependencies***
1. Store front Theme
2. Woocommerce Plugin
_You can install this with WP_CLI_
Run this on the root folder
```bash
# wp-cli
## install storefront theme
wp theme install Storefront
## install woocommerce
wp plugin install woocommerce
```

**Child Theme Creation and Configuration**
All of our work will be done in the child theme folder, so that the parent theme can be updated regularly without losing any of our work.
1. Create style.css and functions.php basic files inside child theme folder

```bash
#from wordpress root folder, switch to main theme folder
cd wp-content/themes
# create child theme directory (Common practice parentthemename-child)
mkdir storefront-child
# cd into the folder and create css and php files
cd storefront-child
touch style.css
touch functions.php
```

- Style.css file
```css
/*
Theme Name:   Storefront Child
Theme URI:    http://example.com/twenty-fifteen-child/
Description:  Storefront Child Theme
Author:       Deepesh Dhakal
Author URI:   https://github.com/deepyes02
Template:     storefront
Version:      1.0.0
License:      GNU General Public License v2 or later
License URI:  http://www.gnu.org/licenses/gpl-2.0.html
Tags:         woocommerce
Text Domain:  storefrontchild
*/
```

- Functions.php File

```php
<?php
/**
 * The main function php file for the child theme
 */
// basic setup complete, the child theme now appears on the themes folder and works
```