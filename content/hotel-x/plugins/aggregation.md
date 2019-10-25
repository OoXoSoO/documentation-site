+++
title = "Aggregation"
pagetitle = "Aggregation"
description = "Aggregate different Suppliers response based on different criteria."
icon = "fa-compress"
weight = 3
alwaysopen = false
+++

**Aggregation plugins** extends [HotelX](/hotel-x/) allowing filtering `Supplier` options and responses using different business rules.

### KeyFilter

Filters `Supplier` options based on _field keys_ applying a selector _function_ over _field values_.

It's based on [SQL Aggregate Functions](https://www.postgresql.org/docs/current/static/functions-aggregate.html) but filtering, not aggregating.

* **_Field Keys_** as a combination of:
  * currency
  * supplier
  * hotel
  * market
  * board
  * payment
  * room
  * promotion
  * supplement
  * surcharges
  * rateRules
  * cancelPolicy

### Parameters

|key|value type|condition|description|
|---|----|----|---|
|primaryKey|string|mandatory|It is the criteria used to aggregate, the value is a set of criteria separated by commas, the possible values are:<br>example: “hotel,supplier,room”|


### Processor

It's implemented as a [Processor plugin](/hotel-x/plugins/processor)

### Execution example

```
{
    "plugins": {
        "step": "RESPONSE_OPTION/RESPONSE",
        "pluginsType": [
            {
                "type": "AGGREGATION",
                "name": "cheapest_price",
                "parameters": [
                    {
                        {"key": "primaryKey","value": "hotel,supplier,room"}
                    }
                ]
            }
        ]
    }
}
```
