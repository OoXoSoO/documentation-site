{
  "title": "PriceBreakdown",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Date!",
      "name": "effectiveDate",
      "url": "/hotelx/reference/scalars/date",
      "description": "Start date in which the price becomes effective.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Date!",
      "name": "expireDate",
      "url": "/hotelx/reference/scalars/date",
      "description": "Expire date of price.",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Price!",
      "name": "price",
      "url": "/hotelx/reference/objects/price",
      "description": "Specifies the daily price.",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "PriceBreakdown",
  "hideGithubLink": true
}
Information about daily price.
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
