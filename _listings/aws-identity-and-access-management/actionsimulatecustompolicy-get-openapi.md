---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Simulate Custom Policy
  version: 1.0.0
  description: |-
    Simulate how a set of IAM policies and optionally a resource-based policy works with
          a list of API actions and AWS resources to determine the policies' effective permissions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetContextKeysForCustomPolicy:
    get:
      summary: Get Context Keys For Custom Policy
      description: Gets a list of all of the context keys referenced in the input
        policies.
      operationId: getContextKeysForCustomPolicy
      x-api-path-slug: actiongetcontextkeysforcustompolicy-get
      parameters:
      - in: query
        name: PolicyInputList.member.N
        description: A list of policies for which you want the list of context keys
          referenced in those      policies
        type: string
      responses:
        200:
          description: OK
      tags:
      - Context Keys For Custom Policies
  /?Action=SimulateCustomPolicy:
    get:
      summary: Simulate Custom Policy
      description: |-
        Simulate how a set of IAM policies and optionally a resource-based policy works with
              a list of API actions and AWS resources to determine the policies' effective permissions.
      operationId: simulateCustomPolicy
      x-api-path-slug: actionsimulatecustompolicy-get
      parameters:
      - in: query
        name: ActionNames.member.N
        description: A list of names of API actions to evaluate in the simulation
        type: string
      - in: query
        name: CallerArn
        description: The ARN of the IAM user that you want to use as the simulated
          caller of the APIs
        type: string
      - in: query
        name: ContextEntries.member.N
        description: A list of context keys and corresponding values for the simulation
          to use
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only after     you
          receive a response indicating that the results are truncated
        type: string
      - in: query
        name: MaxItems
        description: (Optional) Use this only when paginating results to indicate
          the     maximum number of items you want in the response
        type: string
      - in: query
        name: PolicyInputList.member.N
        description: A list of policy documents to include in the simulation
        type: string
      - in: query
        name: ResourceArns.member.N
        description: A list of ARNs of AWS resources to include in the simulation
        type: string
      - in: query
        name: ResourceHandlingOption
        description: Specifies the type of simulation to run
        type: string
      - in: query
        name: ResourceOwner
        description: An AWS account ID that specifies the owner of any simulated resource
          that does not      identify its owner in the resource ARN, such as an S3
          bucket or object
        type: string
      - in: query
        name: ResourcePolicy
        description: A resource-based policy to include in the simulation provided
          as a string
        type: string
      responses:
        200:
          description: OK
      tags:
      - Custom Policies
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