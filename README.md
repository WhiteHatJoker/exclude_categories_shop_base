# Excluding certain categories from the base shop page #
If you have set the WooCommerce Settings -> Shop Page Display to show categories & subcategories, you may notice that your base shop page automatically shows all parent categories. This PHP snippet maybe useful if you would like to remove certain categories from the view on shop page.
## Installation ##
1. Copy over the code in the current repository to your WordPress functions.php or woo-config.php files.
2. Go to your Wordpress Admin Panel -> Products -> Categories and note down the slugs of categories that you would like to hide on your shop page.
3. Place the noted slugs into the array of slugs on line 14 of functions.php
