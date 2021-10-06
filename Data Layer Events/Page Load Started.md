# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Page Load Started",
    "affiliate_id": "<affiliate_id>",
    "bread_crumbs": "<bread_crumbs>",
    "content_owner": "<content_owner>",
    "country": "<country>",
    "day_of_week": "<day_of_week>",
    "language": "<language>",
    "page_location": "<page_location>",
    "page_name": "<page_name>",
    "page_name_detailed": "<page_name_detailed>",
    "page_title": "<page_title>",
    "page_type": "<page_type>",
    "page_type_merchandising": "<page_type_merchandising>",
    "site_country": "<site_country>",
    "site_language": "<site_language>",
    "site_name": "<site_name>",
    "site_section": "<site_section>",
    "site_type": "<site_type>",
    "sub_section": "<sub_section>",
    "sub_section_level_2": "<sub_section_level_2>",
    "sub_section_level_3": "<sub_section_level_3>",
    "url_full": "<url_full>",
    "url_hash": "<url_hash>",
    "url_path": "<url_path>",
    "url_query_string": "<url_query_string>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|bread_crumbs|string||Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|content_owner|string||XX product management, marketing, vendor name|||||||
|country|string|The country the site is associated with.||||||||
|day_of_week|string|The day of the week the activity occured.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_name|string||product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_name_detailed|string||product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type|string|The type of page currently viewed.|home, pdp, article|||||||
|page_type_merchandising|string||Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|site_country|string||US, CA, FR, UK|^[A-Z]{2}$||||||
|site_language|string||en-us, en-gb, ch-cn, fr-ca, fr-fr, da|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
|site_name|string||Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|site_type|string||Prospecting, Shop, Members, Brand|||||||
|sub_section|string||Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|sub_section_level_2|string||Shop &gt; Kids &gt; Tops, Shop &gt; Mens &gt; Shoes|||||||
|sub_section_level_3|string||Shop &gt; Kids &gt; Tops &gt; Tees, Shop &gt; Mens &gt; Shoes &gt; Oxfords|||||||




