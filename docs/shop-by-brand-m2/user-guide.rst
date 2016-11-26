================
User Guide
================

By Mageplaza you can find many extensions that cane help online stores improve customers search such as `Magento 2 Layered Navigation`_ and `Magento 2 Advanced Search`_ extension, and `Magento 2 Shop by Brand`_ extension is also one of the such great tool. Similar to the navigation, Shop by Brand allows fitering by product attributes, but they are neither color or material or any physical features of the product. The plugin bases on brands (manufacturers) the products are made by. 

In this helpful Mageplaza documentation, you will achieve the user guide of **How to use** and **How to config** on the frontend and backend of Shop by Brand Magento 2 module. 


How to use 
---------------

As soon as installing Shop by Brand completely, your customers can easily search all products under the favourite brands in your inventory. Especially, on its interface, there are two ways of shopping by brand: "search via box" and "search via alphabet". You will follow these ways here.

Search Box
^^^^^^^^^^^^^^^^^^^

The search box on Magento 2 Shop by Brand has some functionalities that alike to Magento 2 Ajax Search by Mageplaza. In the box, entering some words of the brand name and acheiving the drop-down results instantly on the current page.

.. image:: https://i.imgur.com/jcxg8N5.gif

The brand results comes with Brand Logo, Brand Image and Brand Description. 

.. image:: https://i.imgur.com/TiE2DyN.png

Alphabet Search
^^^^^^^^^^^^^^^^^^^^^^^

Alphabet Search, placed under Search Box, is represented including "Show All" and the alphabets. Depending on the first characteristic of the brand name, the user will tap on the respective button.

.. image:: https://i.imgur.com/p0Xb3sb.gif

How to config
------------------

Login to the backend of Magento 2 Shop by Brand. To cover full of the configuration as an administrator, you need to follow 3 parts: 

* Settings
* Create new brand
* Assign brand to product

Settings
^^^^^^^^^^^^^^^^^^^

**Settings** tab is a bunch of the basic configuration you need to set up firstly. 

* Go to `Shop by Brand > Settings`
* Expand **General** section, please do the following:
  * `Enable` the module when choosing "Yes" to allow customers shop by brand
  * From the existing list of product attribute, set `Select Brand's Product Attribbute	to the correct choice. In this guide, "mp_brand" is the option you have to select

    .. note:: To create a new product attribute under "Brand" name, please read `How to Create Product Attribute Sets in Magento 2`_ topic in Magento 2 Tutorial by Mageplaza.

  * Enter `Brand Titles`.
  * Enter `Url Prefix`, if passing it, the default (brand) is applied
  * Select relevant color for the `Background color` of Shop by Brand's interface 
  * Show `Featured page format` as "Net" or "Slider" that depends on your store's design
* Expand **Search Settings** section,
  * Set `Min chars test`, that should be usually 1 or 2
  * Limit `Maximum Query Result` that match with the given request
  * Make brand image visible on the search by selecting "Yes"
  * Set `Max Letter Number` in the search box
.. image:: https://i.imgur.com/YMy5mJ4.png

Create new brand
^^^^^^^^^^^^^^^^^^^^^^

* On the Admin Panel, `Store > Attributes > Product`.
* Under **Attribute Code** column, search and choose "mp_brand", you will navigation its workplace.
* All brands are listed under **Manage Options** section, click on **Add option** on the bottom of the list, right after, a new row will appear.
* Tap **Advanced Option** to open the "Brands" page.

.. image:: https://i.imgur.com/WhHxzCr.gif

* On the right corner, click on **Add New Brand**.
* Expand **Brand Information** section,
  * Set `Name` for the new brand
  * Create **URL Key**
  * Upload `Brand Image` from your computer
  * Enter `Short Description` (appear on the search result) and `Description` (appear on Brand Listing) 
  * Allow showing as a statis block on anywhere of your page. You can disable it if need
  * In the `Enable` field, choose "Yes" to show the new brand
* Expand **Meta Information** section, you can complete all fields for your better SEO, including:
  * Meta Title
  * Meta Description
  * Meta Keywords
* `Save Brand` to ensure that creating the new brand is successful.

  .. note:: For the existing brands, you can edit their information via **Advanced Option** button.

Assign brand to product 
^^^^^^^^^^^^^^^^^^^^^^^^^

This guide helps you classify what brand a product is mage by.

* On the Admin Panel, `Product > Inventory > Catalog`.
* Select an exact product you want to assign, and open `Edit` mode under **Action** column.
* On the settings page of the product, you will see `Brand` field that allow assign a corresponding brand to that product.

.. image:: https://i.imgur.com/B4c9jeE.png

.. _Magento 2 Shop by Brand: https://www.mageplaza.com/magento-2-shop-by-brand/
.. _Magento 2 Layered Navigation: https://www.mageplaza.com/magento-2-layered-navigation-extension/
.. _Magento 2 Advanced Search: https://www.mageplaza.com/magento-2-search-extension/
.. _How to Create Product Attribute Sets in Magento 2: https://www.mageplaza.com/kb/how-to-create-product-attribute-sets-magento-2.html