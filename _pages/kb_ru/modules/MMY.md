---
lang: ru
layout: article_with_sidebar
updated_at: '2018-06-14 17:04 +0400'
identifier: ref_4SKmwOLz
title: Марка / Модель / Год изготовления (Make/Model/Year)
order: 310
published: false
---
Модуль [Марка/Модель/Год изготовления (Make/Model/Year)](https://market.x-cart.com/addons/make-model-year.html "Марка / Модель / Год изготовления (Make/Model/Year)") добавляет 4 уровня поисковых фильтров, запоминает фильтры поиска незарегистрированных покупателей и просмотренные автомобили зарегистрированных покупателей. Модуль предназначен для магазинов, продающих авто и мотозапчасти, но подходит и для других магазинов, товары в которых подразделяются на группы (компьютеры, смартфоны, копировальные аппараты и т.п.).

В магазине появляется секция **Выберите автомобиль**, которая присутствует на всех страницах магазина. Покупатель выбирает марку, модель, год выпуска и объём двигателя автомобиля и получает список соответствующих товаров.

Модуль **Марка/Модель/Год изготовления (Make/Model/Year)** платный, приобретите лицензию в Маркетплейсе и {% link "установите модуль" ref_gpeZtm28 %}. По ссылке **Настройки** открывается раздел параметров модуля.

![installed.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/installed.png)

Сначала настройте модуль, затем создайте уровни и добавьте товары.

Настройка модуля

![settings.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/settings.png)

{:.ui.compact.celled.small.padded.table}

| **Количество уровней, используемых в фильтре (2,3,4)** | Выберите 2,3 или 4 уровня (марка, модель, год выпуска и объём двигателя), которые настроите для товаров. |
| **Название уровня**| Полям по умолчанию даны названия, подходящие для магазина автомобильной тематики. Переименуйте эти поля, если настраиваете модуль не для автомобилей, а для других товаров.|
| **Ширина баннера** | Максимально возможная ширина баннера на странице уровня. Стандартное значение 500 можно изменить. |
| **Высота баннера** | Максимально возможная высота баннера на странице уровня. Стандартное значение 200 можно изменить. |
| **Использовать отдельную вкладку на странице товара для перечня групп** | Если опция включена, автомобили, для которых подходит деталь, будут перечислены на отдельной вкладке **Совместимость** на странице товара в магазине. Вкладка **Совместимость** появится и на странице товара в панели управления магазина. Если опция отключена - автомобили, для которых подходит деталь, будут перечислены на вкладке **Описание** на странице товара в магазине. | 
| **Сортировка уровня** | Выберите режим сортировки результатов поиска на каждом уровне - в _алфавитном порядке, с 0 до 9_ или _в обратном алфавитном порядке, с 9 до 0_. |

{% note info %}
With the **Use separate tab for the fitment on the product page** option enabled each product will gain a separate **Fitment** tab that will be displayed onthe product details page both in the admin back-end and customer frontend.
<div class="ui stackable two column grid">
  <div class="column" markdown="span">![fitment-admin.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/fitment-admin.png)</div>
  <div class="column" markdown="span">![fitment-frontend.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/fitment-frontend.png)</div>
</div>
{% endnote %}

When the **Make/Model/Year** module settings are configured you can proceed with setting up the filter levels and populating the module with products. 

To configure the filters go to the **Catalog** -> **Make/Model/Year/Engine** page of the admin back-end and start adding the filters of Level 1 (**Makes**).

![make.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/make.png)

To add a **Make** click on the **'New Make'** button and name the Make in a new line. When you add all the makes, click **Save changes**.  

Likewise you can proceed with the next levels configuration (Model/Year/Engine). For this purpose you'll need to click the **Manage Model** link opposite to the **Make**, **Manage Year** link opposite to the **Model** and so on and add the positions for the next levels. 

<div class="ui stackable three column grid">
  <div class="column" markdown="span">![model.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/model.png)</div>
  <div class="column" markdown="span">![year.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/year.png)</div>
  <div class="column" markdown="span">![engine.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/engine.png)</div>
</div>

When the levels are configured, you can add products on the very last step by clicking the **Manage Products** link in the end. 

* If the products are already added/uploaded to the store click the **'Add product'** button and choose the products that meet the filters you configured from a list in a pop-up.
  
  ![select_products.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/select_products.png)
  
  
* If the products are not uploaded to the store as yet, you can import them with a .csv file using the guides from {% link "CSV import: Products" ref_WmJBfwxA %}.
  The fields that should be added to a .csv file to populate the module with products should be as follows:
  
  ![csv.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/csv.png)
  
  
  The fields' names in the .csv file should correspond with the level names you set on the **Make/Model/Year Module** settings page.
  
  {% note info %}
  
  If the value **ALL** is specified for a field, the SKU will be added to all existing level values (works for predefined levels only). 
  
  e.g. 
  make/model/year : all/A5/2012
  
  In this case new items will be added to all existing Make levels (make1/A5/2012, … makeNN/A5/2012). You can even import values as make/model/year: all,all,all and the SKU will be added to all existing Make/Model/Year levels. 
  
  {% endnote %}
  
  You can upload products to the module even without configuring the module levels beforehand. The levels and their values will be added to the **Catalog** -> **Make/Model/Year/Engine** section automatically from the .csv file you imported. 
  
Starting from Level 2 (**Model**), each sublevel has a special **Level info** page, that if configured will be displayed in the storefront depending on the selected filters. It’s especially useful if you want to provide your customers with additional information on Make, Model or particular vehicle when they select it. Due to flexible settings, you can set the same page, for example, for all models and years or a separate page for each model (and even year). Using a simple interface you can set the page Title, Image and Description. 

![level_info.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/level_info.png)

When a customer clicks to filter the parts, he will be redirected to the corresponding landing page (**Level info** page) with its own name, image and information. This page will also contain the list of spare parts for the vehicle specified by the customer. 

<div class="ui stackable two column grid">
  <div class="column" markdown="span">![landing_admin.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/landing_admin.png)</div>
  <div class="column" markdown="span">![landing-customer.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/landing-customer.png)</div>
</div>

If the **Level page** is not configured for a sublevel, the module will display the search results depending on the filters set by a customer.

![customer_filters.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/customer_filters.png)

The **Make/Model/Year** filters show up on all pages in your online store. A customer selects a make of a product, a model, a year and an engine using convenient modern selectors and gets a list of products with the set characteristics.

![filters-fontend.png]({{site.baseurl}}/attachments/ref_0Esu2RNW/filters-fontend.png)

Registered customers can save their vehicles in the account with the **'Remember my vehicle'** checkbox. Next time they come to your store, they will see the parts for their vehicles right away without the need to use filters.