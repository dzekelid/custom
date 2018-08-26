---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddCustomAttributes:
    get:
      summary: Add Custom Attributes
      description: Adds additional user attributes to the user pool schema.
      operationId: addCustomAttributes
      x-api-path-slug: actionaddcustomattributes-get
      parameters:
      - in: query
        name: CustomAttributes
        description: An array of custom attributes, such as Mutable and Name
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to add custom            attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attributes
---