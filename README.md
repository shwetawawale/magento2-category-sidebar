# Category Sidebar for Magebto 2 

This extension will add the ability to show category tree sidebar (on category page and search result page). The module has configuration options in the Magento 2 admin config page.

## Installation with composer
* (in progress...)

## Installation without composer
* Download zip file of this extension
* Place all the files of the extension in your Magento 2 installation in the folder `app/code/JQ/CategorySidebar`
* Enable the extension: `php bin/magento --clear-static-content module:enable JQ_CategorySidebar`
* Upgrade db scheme: `php bin/magento setup:upgrade`
* Clear cache

## Configuration
* Enable module 
* Decide whether to show the title of the "Categories" block
* Select the type of category tree ( Default Category / Current Category Children / Current Category Parent Children / Only Branch of Current Category )
* You can show (or hide) the number of products in a given category, e.g. Jackets (20)
* Select children depth level
* Categories will appear in col.left sidebar of the theme
