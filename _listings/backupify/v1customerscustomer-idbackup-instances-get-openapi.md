---
swagger: "2.0"
x-collection-name: Backupify
x-complete: 0
info:
  title: Backupify Retrieves a list of backup_instances associated with the specified
    customer
  description: It is only possible to retrieve backup_instances for customers you
    are authorized to access. Records are returned in ascending order (by id), with
    a default of 20 per page. Links to the next, previous, first, and last pages can
    be found in the response headers.
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/authenticate_customer:
    get:
      summary: A simple method to test authentication of a customer access token.
      description: A simple method to test authentication of a customer access token..
      operationId: getV1AuthenticateCustomer
      x-api-path-slug: v1authenticate-customer-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted for customer
      responses:
        200:
          description: OK
      tags:
      - V1
      - Authenticate
      - Customer
  /v1/customers:
    get:
      summary: Retrieve a list of customers associated with the authenticated vendor
      description: Requires Access Token granted from client credentials. Records
        are returned in ascending order (by id), with a default of 20 per page. Links
        to the next, previous, first, and last pages can be found in the response
        headers.
      operationId: getV1Customers
      x-api-path-slug: v1customers-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
    post:
      summary: Create a new customer instance identified by the given {name} identifier
      description: Create a new customer instance identified by the given {name} identifier.
      operationId: postV1Customers
      x-api-path-slug: v1customers-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: formData
        name: customer[email]
        description: Email address associated with the customer
      - in: formData
        name: customer[name]
        description: Vendor provided ID uniquely identifying customer
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
  /v1/customers/{customer_id}:
    get:
      summary: Retrieves the customer identified by customer_id
      description: Requires Access Token granted from client credentials.
      operationId: getV1CustomersCustomer
      x-api-path-slug: v1customerscustomer-id-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: customer_id
        description: ID of the customer to retrieve
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
    put:
      summary: Update a customer instance identified by the given customer_id
      description: Update a customer instance identified by the given customer_id.
      operationId: putV1CustomersCustomer
      x-api-path-slug: v1customerscustomer-id-put
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: formData
        name: customer[name]
        description: Vendor provided ID uniquely identifying customer
      - in: path
        name: customer_id
        description: ID of the customer to modify
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
  /v1/customers/{customer_id}/backup_instances:
    get:
      summary: Retrieves a list of backup_instances associated with the specified
        customer
      description: It is only possible to retrieve backup_instances for customers
        you are authorized to access. Records are returned in ascending order (by
        id), with a default of 20 per page. Links to the next, previous, first, and
        last pages can be found in the response headers.
      operationId: getV1CustomersCustomerBackupInstances
      x-api-path-slug: v1customerscustomer-idbackup-instances-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: customer_id
        description: ID of the customer to retrieve backup_instances for
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
      - Backup
      - Instances
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