---
description: >-
  Follow this process for each store view, that has had data migrated by
  Salecto.
---

# Redirects



* Rough match between old and new URL structure here: [https://app.getredirects.com/login](https://app.getredirects.com/login).
  * Can be done either via existing /sitemap.xml, .csvl file from Google Analytics or CSV-file from crawl \(Screaming Frog\).
  * Check if "\[domian.com\]/sitemap.xml" exists. If not : Ask the customer to link: "online@salecto.dk" to their Google Analytics account.
  * Log in to account and go to Behavior &gt; Website content &gt; All pages &gt; Select a date range \(eg. last 12 months\) and export.
  * Run a crawl of previous shop with Screaming Frog and save CSV-file.
  * Edit the output file so that it consists of 2 columns and send to the customer: Old URL \| New URL



* When the file is returned from the customer, the following must be done:
  * Make sure the domain name in the "New URL" column is not the staging-shop URL \(It must be the same as the "Old URL" domain\).
  * Remove top row \(with column names\).
  * Add a third column with "301" in all rows.
  * Check if there are any redundant redirects, by checking in Excel if "New URL" is the same as "Old URL".
  * Check for broken links: [https://ahrefs.com/broken-link-checker](https://ahrefs.com/broken-link-checker).

  
**NOTE:** Regarding DanDomain

https://support.dandomain.dk/webshop-hjaelp/guides/google/google-webmastervaerktoejer/\#tilfoj\_sitemap\_filer

**All DanDomain webshops have a minimum of 3 sitemaps:**

* http://www.domain.com/shop/GoogleSitemapProducts.asp
* http://www.domain.com/shop/GoogleSitemapCategories.asp
* http://www.domain.com/shop/GoogleSitemapPages.asp

You can copy the URLs from these sitemaps and compile them into one CSV file which you can upload to GetRedirects, via any Excel hoist.  

**NOTE:** Regarding Golden Planet

https://www.goldenplanet.dk/support/sogemaskineoptimering/google-sitemap/ 

**For Golden Planet shops, their XML Sitemap is here:** https: //domæne.dk/sitemap-index.xml

Although not all URLs are in one XML file, GetRedirects can easily figure out the underlying XML files itself.



