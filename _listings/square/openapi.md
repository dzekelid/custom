---
swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/customers:
    get:
      summary: ListCustomers
      description: Lists a business's customers.
      operationId: ListCustomers
      x-api-path-slug: v2customers-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: query
        name: cursor
        description: A pagination cursor returned by a previous call to this endpoint
      responses:
        200:
          description: OK
      tags:
      - ListCustomers
    post:
      summary: CreateCustomer
      description: |-
        Creates a new customer for a business, which can have associated cards on file.

        You must provide __at least one__ of the following values in your request to this
        endpoint:

        - `given_name`
        - `family_name`
        - `company_name`
        - `email_address`
        - `phone_number`

        This endpoint does not accept an idempotency key. If you accidentally create
        a duplicate customer, you can delete it with the
        [DeleteCustomer](#endpoint-deletecustomer) endpoint.
      operationId: CreateCustomer
      x-api-path-slug: v2customers-post
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - CreateCustomer
  /v2/customers/{customer_id}:
    delete:
      summary: DeleteCustomer
      description: Deletes a customer from a business, along with any linked cards
        on file.
      operationId: DeleteCustomer
      x-api-path-slug: v2customerscustomer-id-delete
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: path
        name: customer_id
        description: The ID of the customer to delete
      responses:
        200:
          description: OK
      tags:
      - Customer
    get:
      summary: RetrieveCustomer
      description: Returns details for a single customer.
      operationId: RetrieveCustomer
      x-api-path-slug: v2customerscustomer-id-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: path
        name: customer_id
        description: The ID of the customer to retrieve
      responses:
        200:
          description: OK
      tags:
      - RetrieveCustomer
    put:
      summary: UpdateCustomer
      description: |-
        Updates the details of an existing customer.
        The ID of the customer may change if the customer has been merged into another customer.

        You cannot edit a customer's cards on file with this endpoint. To make changes
        to a card on file, you must delete the existing card on file with the
        [DeleteCustomerCard](#endpoint-deletecustomercard) endpoint, then create a new one with the
        [CreateCustomerCard](#endpoint-createcustomercard) endpoint.
      operationId: UpdateCustomer
      x-api-path-slug: v2customerscustomer-id-put
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customer_id
        description: The ID of the customer to update
      responses:
        200:
          description: OK
      tags:
      - Customer
  /v2/customers/{customer_id}/cards:
    post:
      summary: CreateCustomerCard
      description: |-
        Adds a card on file to an existing customer. In the United States
        Square takes care of automatically updating any cards on file that might
        have expired since you first attached them to a customer.
      operationId: CreateCustomerCard
      x-api-path-slug: v2customerscustomer-idcards-post
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customer_id
        description: The ID of the customer to link the card on file to
      responses:
        200:
          description: OK
      tags:
      - CreateCustomerCard
  /v2/customers/{customer_id}/cards/{card_id}:
    delete:
      summary: DeleteCustomerCard
      description: Removes a card on file from a customer.
      operationId: DeleteCustomerCard
      x-api-path-slug: v2customerscustomer-idcardscard-id-delete
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: path
        name: card_id
        description: The ID of the card on file to delete
      - in: path
        name: customer_id
        description: The ID of the customer that the card on file belongs to
      responses:
        200:
          description: OK
      tags:
      - CustomerCard
---