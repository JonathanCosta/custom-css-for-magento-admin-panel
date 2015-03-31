# How to best integrate `custom.css` in Magento #
One can easily be tempted to download this `custom.css` file and then directly overwrite the custom.css file in the `skin/adminhtml/default/default` directory. <br />
Please **resist this urge**, you will regret this later, for it will not survive any updates of [Magento](http://www.magentocommerce.com/wiki/). <br />
The easiest way to build **_your own custom admin theme module_** in Magento is:
  1. Download [Ivan Weiler’s](http://inchoo.net/author/weiler/)  `admintheme_example.rar` from [inchoo.net](http://inchoo.net/ecommerce/magento/custom-admin-theme-in-magento/).
  1. Follow the instructions on [this blog post](http://inchoo.net/ecommerce/magento/custom-admin-theme-in-magento/): where to copy the files.
  1. Make also a custom theme folder in: `skin/adminhtml/default/`  -> **your-theme**
  1. Rename the `custom-0.1.css` file to `custom.css`, and copy the file to the **_your-theme_** folder; the one that you just created.
  1. When done correctly a “Admin Theme” option will appear in Magento Admin Panel -> System -> Configuration -> General -> Design (Default Config scope). Just fill in the name of your theme there.
## Extra options ##
  * Create an **images folder** in **_your-theme_** folder. For the `custom.css` stylesheet I replaced some of the default UI icons with some fresher looking ones. They're from an iconset named [Fugue icons](http://p.yusukekamiyamane.com/), and made by Yusuke Kamiyamane: exceptionally well-thought-out and craftily executed icons.
  * Create a **type folder** in **_your-theme_** folder. The [Luxi-Sans@fontface kit](http://www.fontsquirrel.com/fonts/Luxi-Sans) that is referred to in the stylesheet can be downloaded at fontsquirrel.
  * Download a [light grey diagonal-striped tiling background-image](http://code.google.com/p/custom-css-for-readability/downloads/list)
### Details ###
    * [sample 0.1.css](Sample.md) Current and first version: 0.1 - _March 2011_
by [Atelier Bram de Haan](http://www.atelierbramdehaan.nl/)