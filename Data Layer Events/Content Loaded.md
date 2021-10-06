# Content Loaded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Content Loaded",
    "content_author": "<content_author>",
    "content_author_merchandising": "<content_author_merchandising>",
    "content_date_merchandising": "<content_date_merchandising>",
    "content_id": "<content_id>",
    "content_id_merchandising": "<content_id_merchandising>",
    "content_licensor": "<content_licensor>",
    "content_modified_date": "<content_modified_date>",
    "content_publish_date": "<content_publish_date>",
    "content_title": "<content_title>",
    "content_title_merchandising": "<content_title_merchandising>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content_author|string||Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_author_merchandising|string||Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_date_merchandising|string||2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_licensor|string||HBO, Disney|||||||
|content_modified_date|string||1-1-2020, 2-2-2019|||||||
|content_publish_date|string||2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_title|string||50 ways to use jello, Another look at pandas, Year end giving|||||||
|content_title_merchandising|string||50 ways to use jello, Another look at pandas, Year end giving|||||||




