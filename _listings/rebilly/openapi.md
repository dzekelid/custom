---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 1
info:
  title: Rebilly
  description: -introductionthe-rebilly-api-is-built-on-http---our-api-is-restful---it-has-predictableresource-urls---it-returns-http-response-codes-to-indicate-errors---it-alsoaccepts-and-returns-json-in-the-http-body---you-can-use-your-favoritehttprest-library-for-your-programming-language-to-use-rebillys-api-oryou-can-use-one-of-our-sdks-currently-available-in-phphttpsgithub-comrebillyrebillyphpand-chttpsgithub-comrebillyrebillydotnetclient--authenticationwhen-you-sign-up-for-an-account-you-are-given-your-first-api-key-you-can-generate-additional-api-keys-and-delete-api-keys-as-you-mayneed-to-rotate-your-keys-in-the-future--you-authenticate-to-therebilly-api-by-providing-your-secret-key-in-the-request-header-rebilly-offers-three-forms-of-authentication--private-key-json-web-tokens-andpublic-key--private-key-authenticates-each-request-by-searching-for-the-presenceof-an-http-header-rebapikey--jwt-authenticates-each-request-by-the-http-header-authorization--public-key-authenticates-by-the-http-header-rebauth-read-more-on-this-below-rebilly-also-offers-json-web-tokens-jwt-authentication-where-you-can-controlthe-specific-granular-permissions-and-expiration-for-that-jwt---we-call-our-resourcefor-generating-jwt-sessionstagsessions-rebilly-also-has-a-clientside-authentication-scheme-that-uses-anapiuser-and-hmacsha1-signature-only-for-the-tokens-resource-sothat-you-may-safely-create-tokens-from-the-clientside-without-compromisingyour-secret-keys-never-share-your-secret-keys--keep-them-guarded-and-secure-the-clientside-authentication-scheme-uses-one-http-header-named-rebauth--redocinject-securitydefinitions--php-sdkfor-all-php-sdk-examples-provided-in-this-spec-you-will-need-to-configure-client-you-may-do-it-like-thisphpclient--new-rebillyclient----apikey--yourapikeyhere----baseurl--httpsapi-rebilly-com
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /custom-fields/{resource}:
    get:
      summary: Retrieve Custom Fields
      description: Retrieve a schema of Custom Fields for the given resource type
      operationId: custom_fields.resource.get
      x-api-path-slug: customfieldsresource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Custom
      - Fields
  /custom-fields/{resource}/{name}:
    delete:
      summary: Delete a custom field
      description: Delete a custom field by its name
      operationId: custom_fields.resource.name.delete
      x-api-path-slug: customfieldsresourcename-delete
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Field
    get:
      summary: Retrieve a Custom Field
      description: Retrieve a schema of the given Custom Field for the given resource
        type
      operationId: custom_fields.resource.name.get
      x-api-path-slug: customfieldsresourcename-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Custom
      - Field
    put:
      summary: Create or alter a Custom Field
      description: Create or alter a schema of the given Custom Field for the given
        resource type.
      operationId: custom_fields.resource.name.put
      x-api-path-slug: customfieldsresourcename-put
      parameters:
      - in: body
        name: body
        description: Custom Fields schema of the given resource type
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Alter
      - Custom
      - Field
  /custom-events:
    get:
      summary: Retrieve a list of custom events
      description: Retrieve a list of custom events
      operationId: retrieve-a-list-of-custom-events
      x-api-path-slug: customevents-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Custom
      - Events
    post:
      summary: Create a custom event
      description: Create a custom event
      operationId: create-a-custom-event
      x-api-path-slug: customevents-post
      parameters:
      - in: body
        name: body
        description: Custom event resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Event
  /custom-events/{id}:
    delete:
      summary: Delete a custom event
      description: Delete a custom event with predefined identifier string
      operationId: delete-a-custom-event-with-predefined-identifier-string
      x-api-path-slug: customeventsid-delete
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Event
    get:
      summary: Retrieve a custom event
      description: Retrieve a custom event with predefined identifier string
      operationId: retrieve-a-custom-event-with-predefined-identifier-string
      x-api-path-slug: customeventsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Custom
      - Event
    put:
      summary: Create a custom event with predefined ID
      description: Create a custom event with predefined identifier string
      operationId: create-a-custom-event-with-predefined-identifier-string
      x-api-path-slug: customeventsid-put
      parameters:
      - in: body
        name: body
        description: Custom event resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Event
      - Predefined
      - ID
  /custom-events/{id}/rules/history:
    get:
      summary: Retrieve the change history of the set of rules for a custom event
      description: |-
        Retrieve the change history of the set of rules for the selected custom event.
        The history is updated each time you change the rules.
      operationId: retrieve-the-change-history-of-the-set-of-rules-for-the-selected-custom-event-the-history-is-updated
      x-api-path-slug: customeventsidruleshistory-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Change
      - History
      - Of
      - Set
      - Of
      - Rulesa
      - Custom
      - Event
  /custom-events/{id}/rules/history/{version}:
    get:
      summary: Retrieve the record from the change history of the set of rules for
        a custom event
      description: |-
        Retrieve the record from the change history of the set of rules for the selected custom event.
        A history record is created each time you change the rules.
      operationId: retrieve-the-record-from-the-change-history-of-the-set-of-rules-for-the-selected-custom-event-a-hist
      x-api-path-slug: customeventsidruleshistoryversion-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Record
      - From
      - Change
      - History
      - Of
      - Set
      - Of
      - Rulesa
      - Custom
      - Event
  /custom-events/{id}/rules/versions/{version}:
    get:
      summary: Retrieve the version of the set of rules for a custom event
      description: |-
        Retrieve the version of the selected set of rules for the selected custom event.
        The versions are created each time you change the rules.
      operationId: retrieve-the-version-of-the-selected-set-of-rules-for-the-selected-custom-event-the-versions-are-cre
      x-api-path-slug: customeventsidrulesversionsversion-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Version
      - Of
      - Set
      - Of
      - Rulesa
      - Custom
      - Event
  /queue/custom-events:
    get:
      summary: Retrieve a list of scheduled custom events
      description: Retrieve a list of scheduled custom events
      operationId: retrieve-a-list-of-scheduled-custom-events
      x-api-path-slug: queuecustomevents-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Scheduled
      - Custom
      - Events
  /queue/custom-events/{id}:
    delete:
      summary: Delete a scheduled custom event
      description: Delete a scheduled custom event with predefined identifier string
      operationId: delete-a-scheduled-custom-event-with-predefined-identifier-string
      x-api-path-slug: queuecustomeventsid-delete
      responses:
        200:
          description: OK
      tags:
      - Scheduled
      - Custom
      - Event
    get:
      summary: Retrieve a scheduled custom event
      description: Retrieve a scheduled custom event with predefined identifier string
      operationId: retrieve-a-scheduled-custom-event-with-predefined-identifier-string
      x-api-path-slug: queuecustomeventsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Scheduled
      - Custom
      - Event
---