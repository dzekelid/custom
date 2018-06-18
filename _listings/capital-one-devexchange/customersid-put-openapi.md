---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Update a specific existing customer
  description: Updates the specific customer
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customers/{id}/accounts:
    post:
      summary: Create an account
      description: Creates an account for the customer with the id provided
      operationId: creates-an-account-for-the-customer-with-the-id-provided
      x-api-path-slug: customersidaccounts-post
      parameters:
      - in: body
        name: body
        description: Account to be created
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of customer that account will belong to
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
      - ""
      - Accounts
    get:
      summary: Get accounts by customer id
      description: Returns the accounts associated with the specific customer
      operationId: returns-the-accounts-associated-with-the-specific-customer
      x-api-path-slug: customersidaccounts-get
      parameters:
      - in: path
        name: id
        description: ID of customer to fetch accounts for
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
      - ""
      - Accounts
  /accounts/{id}/customer:
    get:
      summary: Get customer that owns the specified account
      description: Returns the customer that the account belongs to.
      operationId: returns-the-customer-that-the-account-belongs-to
      x-api-path-slug: accountsidcustomer-get
      parameters:
      - in: path
        name: id
        description: ID of customer that account will belong to
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Accounts
      - ""
      - Customer
  /customers:
    get:
      summary: Get all customers
      description: Returns the customers that have been assigned to you.
      operationId: returns-the-customers-that-have-been-assigned-to-you
      x-api-path-slug: customers-get
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
    post:
      summary: Create a customer
      description: Creates a customer
      operationId: creates-a-customer
      x-api-path-slug: customers-post
      parameters:
      - in: body
        name: body
        description: Customer to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
  /customers/{id}:
    get:
      summary: Get customer by id
      description: Returns the customer with the specific id
      operationId: returns-the-customer-with-the-specific-id
      x-api-path-slug: customersid-get
      parameters:
      - in: path
        name: id
        description: ID of customer that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
    put:
      summary: Update a specific existing customer
      description: Updates the specific customer
      operationId: updates-the-specific-customer
      x-api-path-slug: customersid-put
      parameters:
      - in: body
        name: body
        description: Updated customer object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of customer that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---