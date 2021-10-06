# Donation Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "Donation Completed",
    "donation_amount": "<donation_amount>",
    "donation_complete_counter": "<donation_complete_counter>",
    "donation_confirmation_id": "<donation_confirmation_id>",
    "donation_frequency": "<donation_frequency>",
    "donation_thank_you_card_type": "<donation_thank_you_card_type>",
    "donation_thank_you_cards_request_count": "<donation_thank_you_cards_request_count>",
    "donation_type": "<donation_type>",
    "ecommerce": {
        "coupon": "<coupon>",
        "currency": "<currency>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "index": "<index>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_id": "<item_id>",
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_variant": "<item_variant>"
            }
        ],
        "transaction_id": "<transaction_id>",
        "value": "<value>"
    },
    "payment_city": "<payment_city>",
    "payment_currency_code": "<payment_currency_code>",
    "payment_method": "<payment_method>",
    "payment_postal_code": "<payment_postal_code>",
    "payment_sequence": "<payment_sequence>",
    "payment_state_or_province": "<payment_state_or_province>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|donation_amount|string||200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|donation_confirmation_id|string|||^[a-zA-Z0-9]{6,20}$|6|20||||
|donation_frequency|string||One Time, Monthly|||||||
|donation_thank_you_card_type|string||Electronic, Physical|||||||
|donation_thank_you_cards_request_count|boolean||TRUE, FALSE|||||||
|donation_type|string||Tribute, General, Fundraiser|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_variant|string|The variant of the item.|Black|||||||
|payment_city|string||Atlanta, New York, Los Angeles, Chicago|||||||
|payment_currency_code|string||USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|payment_method|string||Credit Card, PayPal, Mastercard, Visa, Amex, Discover|||||||
|payment_postal_code|string||53533, 30381, M1R 0E9, M3C 0C1|||||||
|payment_sequence|integer||1, 2, 3, 4, 5||||1|||
|payment_state_or_province|string||WI, GA, NB, ON|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||




