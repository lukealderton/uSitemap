uSitemap
========

This project has been created to provide an on the fly sitemap service for your website, it will add all the pages in your website providing they have a template set and are not chosen to be hidden from the menu. Please note, uSitemap is designed for Umbraco websites running version 4.10.0 or higher because it is an MVC project and does not support the use of masterpages.

The sitemap will include the page URL and the update date as standard, however it will also add page priority and update frequency should you choose to add them to your document type under the alias' of 'sitemapUpdateFreq' and 'sitemapPriority'. You can find the values these parameters accept by looking at the sitemap official website.http://www.sitemaps.org/protocol.html

uSitemap also provides a new data type called 'Sitemap Change Frequency Dropdown' which allows you to add the property to a document type and use it straight away without having to reference to the sitemap website.

uSitemap is distributed under the MIT license which means it can be used for free and distributed in other works however you must provide acknowledgement in the credits.

New in version 2.1:
Added option to show/hide pages and their children where umbracoNaviHide is set.

New in version 2.0:
Re-coded from ground up for faster performance.
Added ability to set root node level when calling the partial.
