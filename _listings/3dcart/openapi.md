---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 1
info:
  title: _3dCartWebAPI
  version: 1.0.0
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CustomerGroups:
    get:
      summary: Get all CustomerGroups
      description: Get all customergroups.
      operationId: CustomerGroups_GetAllCustomerGroups
      x-api-path-slug: 3dcartwebapiv1customergroups-get
      parameters:
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - CustomerGroups
    put:
      summary: This method updates a collection of customer groups in the database.
        No URL parameters should be included.
      description: This method updates a collection of customer groups in the database.
        no url parameters should be included..
      operationId: CustomerGroups_Update
      x-api-path-slug: 3dcartwebapiv1customergroups-put
      parameters:
      - in: body
        name: customergroups
        description: A Json or XML object containing the customer group
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Updates
      - Collection
      - Of
      - Customer
      - Groups
      - In
      - Database
      - ""
      - "No"
      - URL
      - Parameters
      - Should
      - Be
      - Included
    post:
      summary: Adds a new customer group to the system
      description: Adds a new customer group to the system.
      operationId: CustomerGroups_Post
      x-api-path-slug: 3dcartwebapiv1customergroups-post
      parameters:
      - in: body
        name: customergroup
        description: A Json or XML object containing the new customer group
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Customer
      - Group
      - To
      - System
  /3dCartWebAPI/v1/CustomerGroups/{customergroupid}:
    put:
      summary: This method is used to update a single customer group in the database.
        The {id} parameter specifies which customer group to update.
      description: This method is used to update a single customer group in the database.
        the {id} parameter specifies which customer group to update..
      operationId: CustomerGroups_Update
      x-api-path-slug: 3dcartwebapiv1customergroupscustomergroupid-put
      parameters:
      - in: body
        name: customergroup
        description: A Json or XML object containing the customer group
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customergroupid
        description: Customer Group ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Customer
      - Group
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - Customer
      - Group
      - To
      - Update
  /3dCartWebAPI/v1/CustomerGroups/{id}:
    get:
      summary: Get a CustomerGroup
      description: Get a customergroup.
      operationId: CustomerGroups_GetCustomerGroup
      x-api-path-slug: 3dcartwebapiv1customergroupsid-get
      parameters:
      - in: path
        name: id
        description: Customer Group ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - CustomerGroup
    delete:
      summary: Deletes a customer group in the system
      description: Deletes a customer group in the system.
      operationId: CustomerGroups_Delete
      x-api-path-slug: 3dcartwebapiv1customergroupsid-delete
      parameters:
      - in: path
        name: id
        description: Customer Group ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Customer
      - Group
      - In
      - System
  /3dCartWebAPI/v1/CustomerGroups/{id}/Customers:
    get:
      summary: Get Customers from a Customer Group
      description: Get customers from a customer group.
      operationId: Customers_GetCustomerFromCustomerGroup
      x-api-path-slug: 3dcartwebapiv1customergroupsidcustomers-get
      parameters:
      - in: query
        name: city
        description: City of the Customer
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: country
        description: Country name of the Customer
      - in: query
        name: email
        description: Email of the Customer
      - in: query
        name: firstname
        description: Firstname of the Customer
      - in: path
        name: id
        description: Customer Group ID
      - in: query
        name: lastname
        description: Lastname of the Customer
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: phone
        description: Phone of the Customer
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: state
        description: State of the Customer
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Customers
      - From
      - Customer
      - Group
  /3dCartWebAPI/v1/Customers:
    get:
      summary: Get all Customers
      description: Get all customers.
      operationId: Customers_GetAllCustomers
      x-api-path-slug: 3dcartwebapiv1customers-get
      parameters:
      - in: query
        name: city
        description: City of the Customer
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: country
        description: Country name of the Customer
      - in: query
        name: email
        description: Email of the Customer
      - in: query
        name: firstname
        description: Firstname of the Customer
      - in: query
        name: lastname
        description: Lastname of the Customer
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: phone
        description: Phone of the Customer
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: state
        description: State of the Customer
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Customers
    put:
      summary: This method is used to update multiple customers in the system. No
        URL parameters should be included.
      description: This method is used to update multiple customers in the system.
        no url parameters should be included..
      operationId: Customers_Update
      x-api-path-slug: 3dcartwebapiv1customers-put
      parameters:
      - in: body
        name: customers
        description: A Json or XML object containing the new customer
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Multiple
      - Customers
      - In
      - System
      - ""
      - "No"
      - URL
      - Parameters
      - Should
      - Be
      - Included
    post:
      summary: Adds a new customer to the system
      description: Adds a new customer to the system.
      operationId: Customers_Post
      x-api-path-slug: 3dcartwebapiv1customers-post
      parameters:
      - in: body
        name: customer
        description: A Json or XML object containing the new customer
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Customer
      - To
      - System
  /3dCartWebAPI/v1/Customers/{customerid}:
    put:
      summary: This method is used to update a single customer record in the database.
        The {id} parameter specifies which customer record to update.
      description: This method is used to update a single customer record in the database.
        the {id} parameter specifies which customer record to update..
      operationId: Customers_Update
      x-api-path-slug: 3dcartwebapiv1customerscustomerid-put
      parameters:
      - in: body
        name: customer
        description: A Json or XML object containing the new customer
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customerid
        description: Customer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Customer
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - Customer
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Customers/{id}:
    get:
      summary: Get a Customer
      description: Get a customer.
      operationId: Customers_GetAllCustomers
      x-api-path-slug: 3dcartwebapiv1customersid-get
      parameters:
      - in: path
        name: id
        description: Customer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Customer
    delete:
      summary: Deletes a Customer in the system
      description: Deletes a customer in the system.
      operationId: Customers_Delete
      x-api-path-slug: 3dcartwebapiv1customersid-delete
      parameters:
      - in: path
        name: id
        description: Customer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Customer
      - In
      - System
---