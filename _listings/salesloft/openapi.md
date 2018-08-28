swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 1
info:
  title: SalesLoft
  description: salesloft-helps-transform-sales-teams-into-modern-sales-organizations---converting-more-target-accounts-into-customer-accounts
  version: v2
host: api.salesloft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/custom_fields.json:
    get:
      summary: List custom fields
      description: |-
        Fetches multiple custom field records. The records can be filtered, paged, and sorted according to
        the respective parameters.
      operationId: v2.custom_fields.json.get
      x-api-path-slug: v2custom-fields-json-get
      parameters:
      - in: query
        name: field_type
        description: Type of field to fetch
      - in: query
        name: ids
        description: IDs of custom fields to fetch
      - in: query
        name: include_paging_counts
        description: Whether to include total_pages and total_count in the metadata
      - in: query
        name: page
        description: The current page to fetch results from
      - in: query
        name: per_page
        description: How many records to show per page in the range [1, 100]
      - in: query
        name: sort_by
        description: 'Key to sort on, must be one of: created_at, updated_at, name'
      - in: query
        name: sort_direction
        description: 'Direction to sort in, must be one of: ASC, DESC'
      responses:
        200:
          description: OK
      tags:
      - Sales
      - List
      - Custom
      - Fields
    post:
      summary: Create a custom field
      description: Creates a custom field.
      operationId: v2.custom_fields.json.post
      x-api-path-slug: v2custom-fields-json-post
      parameters:
      - in: formData
        name: field_type
        description: The field type of the custom field
      - in: formData
        name: name
        description: The name of the custom field
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Custom
      - Field
  /v2/custom_fields/{id}.json:
    delete:
      summary: Delete a custom field
      description: Deletes a custom field.
      operationId: v2.custom_fields.id.json.delete
      x-api-path-slug: v2custom-fieldsid-json-delete
      parameters:
      - in: path
        name: id
        description: Custom Field ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Custom
      - Field
    get:
      summary: Fetch a custom field
      description: Fetches a custom field, by ID only.
      operationId: v2.custom_fields.id.json.get
      x-api-path-slug: v2custom-fieldsid-json-get
      parameters:
      - in: path
        name: id
        description: Custom Field ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Custom
      - Field
    put:
      summary: Update a custom field
      description: Update a custom field.
      operationId: v2.custom_fields.id.json.put
      x-api-path-slug: v2custom-fieldsid-json-put
      parameters:
      - in: formData
        name: field_type
        description: The field type of the custom field
      - in: path
        name: id
        description: Custom Field ID
      - in: formData
        name: name
        description: The name of the custom field
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Custom
      - Field