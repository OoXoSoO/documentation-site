{
  "title": "TimeoutInput",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "search",
      "url": "/hotelx/reference/scalars/int",
      "description": "Milliseconds before the search connection is closed.",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "quote",
      "url": "/hotelx/reference/scalars/int",
      "description": "Milliseconds before the quote connection is closed.",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "book",
      "url": "/hotelx/reference/scalars/int",
      "description": "Milliseconds before the book connection is closed.",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "HotelXDefaultSettingsDataInput",
      "description": "",
      "url": "/hotelx/reference/inputobjects/hotelxdefaultsettingsdatainput"
    },
    {
      "name": "HotelXCommonSettingsDataInput",
      "description": "",
      "url": "/hotelx/reference/inputobjects/hotelxcommonsettingsdatainput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "TimeoutInput",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
