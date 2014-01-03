= Sitemap
This Magento extension Sitemap extends Mage_Sitemap_Model_Sitemap to generate xml sitemaps including images. This will improve your SEO.

== Compatibility
Successfully tested on Community Edition 1.7.x
Successfully tested on Community Edition 1.6.x
This extension will work on Magento 1.6 and above.
Since Magento 1.6.x the directory Model/Mysql4 is changed by Model/Resource
To enable this extension in 1.5.x and lower you should replace every instance of Resource to Mysql4. (some with and some without capitals) Files to change are Sitemap/etc/config.xml and Sitemap/Model/Resource/Catalog/Product.php And don't forget to change the directory itself.

== Installation
* Download the source code and copy the files in the corresponding Magento folders; 
* mind that you merge the directories… Do not replace the existing directories. :-)
* no Magento existing file is modified.
* clear cache and enjoy 

After installation you can generate a new sitemap via Magento backend >> Catalog >> Google Sitemap. The XML structure of your new sitemap will include a reference to the location of a productimage. 

== Copyright
This Magento Sitemap Extension is licensed under Open Software License ("OSL") v. 3.0

[![Analytics](https://ga-beacon.appspot.com/UA-2000642-17/Sitemap/readme)](https://github.com/igrigorik/ga-beacon)
