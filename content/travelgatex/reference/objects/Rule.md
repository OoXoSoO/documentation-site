{
  "title": "Rule",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "id",
      "url": "/travelgatex/reference/scalars/string",
      "description": "rule identifier",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "name",
      "url": "/travelgatex/reference/scalars/string",
      "description": "rule name",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "MarkupRuleType!",
      "name": "type",
      "url": "/travelgatex/reference/enums/markupruletype",
      "description": "type of the value",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "value",
      "url": "/travelgatex/reference/scalars/float",
      "description": "value applied by this rule",
      "isDeprecated": false,
      "args": null
    }
  ],
  "deprecatedFields": null,
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Rule"
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}