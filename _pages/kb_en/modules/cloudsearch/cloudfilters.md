---
lang: en
layout: article_with_sidebar
updated_at: '2018-04-18 11:33 +0400'
identifier: ref_25POvGjV
title: CloudFilters
order: 100
published: true
---
CloudFilters module is aimed at narrowing down search results and hepling your customers to navigate through a large list of products to find items matching certain filtering criteria. 

Filters are displayed on a category/subcategory page, search page, brands page (if the {% link "Shop by Brand" ref_2LetICls %} module is enabled) and vendors page (for {% link "Multivendor" ref_4ahg5FLK %} edition). The module peculiarity here is that the filters are chosen based on the page they will be displayed at. Hence the filters for one category will differ from the filters for another and both of them will differ from the filters displayed on the search page, etc. The set of filters to be displayed on a page is automatically narrowed down and is build based on the  relevant {% link "product attributes" ref_T90ZcEpP %}, {% link "product tags" ref_6nFoxYf1 %} and {% link "vendor" ref_4ahg5FLK %} info. 

To configure filters open the _Cloudfilters_ tab on the **Catalog** -> **CloudSearch & CloudFilters** page in the Admin area. 

![cloudfilters.png]({{site.baseurl}}/attachments/ref_25POvGjV/cloudfilters.png)

You'll see a screen with 2 tabs - SET UP FILTERS and SMART FILTER SELECTION FOR SEARCH.

![cloudfilters-1.png]({{site.baseurl}}/attachments/ref_25POvGjV/cloudfilters-1.png)

The SET UP FILTERS tab is the main one. It contains filters gathered automatically through your store based on all the product attributes, tags and vendors defined. You can enable/disable the filters and change the filters settings:

<div class="ui stackable two column grid">
  <div class="column" markdown="span">![filter-settings-1.png]({{site.baseurl}}/attachments/ref_25POvGjV/filter-settings-1.png)</div>
  <div class="column" markdown="span">![filter-settings.png]({{site.baseurl}}/attachments/ref_25POvGjV/filter-settings.png)</div>
</div>

If a filter is disabled it's not displayed in the storefront. 
Besides the filters listed in the SET UP FILTERS tab there are default filters (category, price and manufacturer) that are always present in addition to the filters you enabled. 

The SMART FILTER SELECTION FOR SEARCH tab is an advanced filtering system that can be used by the big stores with a wide range of products (and product attributes as a result) to narrow down the filters displayed on the search page in the storefront. Here you can define special filter categories based on customer's search query. As a result, only relevant filters will be shown.

To add a filter category hit the **Add Filter Category** button.

![smart-filter.png]({{site.baseurl}}/attachments/ref_25POvGjV/smart-filter.png)


You'll see a pop-up window where you'll need to define a semantic term and add filters from the list that match this category. Click **Add category** when you are done.

![smart-filter-popup.png]({{site.baseurl}}/attachments/ref_25POvGjV/smart-filter-popup.png)


If semantic terms are configured they override the filters from the SET UP FILTERS tab.

{% note info %}
Semantic terms (categories) should correlate with the whole store category structure or product types to cover a certain group of products and should not coincide with each other. 
{% endnote %}