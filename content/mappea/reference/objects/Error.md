{
  "title": "Error",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "code",
      "url": "/mappea/reference/scalars/string",
      "description": "Error code",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "type",
      "url": "/mappea/reference/scalars/string",
      "description": "Error type",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "description",
      "url": "/mappea/reference/scalars/string",
      "description": "Error description",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "GetUploadedFilesResponse",
      "description": "## GetUploadedFiles",
      "url": "/mappea/reference/objects/getuploadedfilesresponse"
    },
    {
      "name": "GetMappeaStatsResponse",
      "description": "",
      "url": "/mappea/reference/objects/getmappeastatsresponse"
    },
    {
      "name": "OnlyStatusResponse",
      "description": "## Common Items",
      "url": "/mappea/reference/objects/onlystatusresponse"
    },
    {
      "name": "UploadFileResponse",
      "description": "",
      "url": "/mappea/reference/objects/uploadfileresponse"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "Error",
  "hideGithubLink": true
}
Application errors
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
