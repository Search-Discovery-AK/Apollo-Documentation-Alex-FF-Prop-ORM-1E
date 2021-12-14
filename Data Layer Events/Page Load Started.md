# Page Load Started

### 

## Javascript Code
```js
window.appEventDataORME = window.appEventDataORME || [];;;
appEventDataORME.push({
  "event": "Page Load Started",
    "page": {
        "detailedPageName": "<detailedPageName>",
        "internalBusinessOwner": "<internalBusinessOwner>",
        "pageName": "<pageName>",
        "pageTitle": "<pageTitle>",
        "pageType": "<pageType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|detailedPageName|string|Describes the page in more detail than the pageName attribute|product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|internalBusinessOwner|string|Describes the internal team who manages this particular page of the website.|XX product management, marketing, vendor name|||||||
|pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|pageTitle|string|HTML title tag for the page||||||||
|pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||




