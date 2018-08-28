---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get notification schemes paginated
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) list of [notification schemes](https://confluence.atlassian.com/x/8YdKLg) in order by display name.

    ### About notification schemes

    A notification scheme is a list of events and recipients who will receive notifications for those events. The list is contained within the `notificationSchemeEvents` object and contains pairs of `events` and `notifications`:

    *   `event` Identifies the type of event. The events can be [Jira system events](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-eventsEvents) or [custom events](https://confluence.atlassian.com/x/AIlKLg).
    *   `notifications` Identifies the [recipients](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-recipientsRecipients) of notifications for each event. Recipients can be any of the following types:

    *   `CurrentAssignee`
    *   `Reporter`
    *   `CurrentUser`
    *   `ProjectLead`
    *   `ComponentLead`
    *   `User` (the `parameter` is the user key)
    *   `Group` (the `parameter` is the group name)
    *   `ProjectRole` (the `parameter` is the project role ID)
    *   `EmailAddress`
    *   `AllWatchers`
    *   `UserCustomField` (the `parameter` is the ID of the custom field)
    *   `GroupCustomField`(the `parameter` is the ID of the custom field)

    _Note that you should allow for events without recipients to appear in responses._

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the requesting user must have permission to administer at least one project associated with a notification scheme for it to be returned.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/customFieldOption/{id}:
    get:
      summary: Get custom field option
      description: "Returns a custom field option. For example, an option in a cascading
        select list.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
        required:** None."
      operationId: com.atlassian.jira.rest.v2.issue.customfield.CustomFieldOptionResource.getCustomFieldOption_get
      x-api-path-slug: api2customfieldoptionid-get
      parameters:
      - in: path
        name: id
        description: The ID of the custom field option
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Field
      - Option
  /api/2/field:
    post:
      summary: Create custom field
      description: |-
        Creates a custom field.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
      operationId: com.atlassian.jira.rest.v2.issue.FieldResource.createCustomField_post
      x-api-path-slug: api2field-post
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Field
  /api/2/notificationscheme:
    get:
      summary: Get notification schemes paginated
      description: |-
        Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) list of [notification schemes](https://confluence.atlassian.com/x/8YdKLg) in order by display name.

        ### About notification schemes

        A notification scheme is a list of events and recipients who will receive notifications for those events. The list is contained within the `notificationSchemeEvents` object and contains pairs of `events` and `notifications`:

        *   `event` Identifies the type of event. The events can be [Jira system events](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-eventsEvents) or [custom events](https://confluence.atlassian.com/x/AIlKLg).
        *   `notifications` Identifies the [recipients](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-recipientsRecipients) of notifications for each event. Recipients can be any of the following types:

        *   `CurrentAssignee`
        *   `Reporter`
        *   `CurrentUser`
        *   `ProjectLead`
        *   `ComponentLead`
        *   `User` (the `parameter` is the user key)
        *   `Group` (the `parameter` is the group name)
        *   `ProjectRole` (the `parameter` is the project role ID)
        *   `EmailAddress`
        *   `AllWatchers`
        *   `UserCustomField` (the `parameter` is the ID of the custom field)
        *   `GroupCustomField`(the `parameter` is the ID of the custom field)

        _Note that you should allow for events without recipients to appear in responses._

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the requesting user must have permission to administer at least one project associated with a notification scheme for it to be returned.
      operationId: com.atlassian.jira.rest.v2.notification.NotificationSchemeResource.getNotificationSchemes_get
      x-api-path-slug: api2notificationscheme-get
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      - in: query
        name: maxResults
        description: The maximum number of items to return per page
      - in: query
        name: startAt
        description: The index of the first item to return in a page of results (page
          offset)
      responses:
        200:
          description: OK
      tags:
      - Notification
      - Schemes
      - Paginated
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