---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Create Custom Call Handling Rules
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/answering-rule:
    post:
      summary: Create Custom Call Handling Rules
      description: "Creates a custom answering rule for a particular caller ID.\nApp
        Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-100\nRule indexes should be sequential\n\n\n400\nAWR-101\nParameter
        [forwarding.rules[].forwardingNumbers[].id] are duplicated\n\n\n400\nAWR-106\nGreeting
        [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore than one caller with the
        same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can be created\n\n\n400\nAWR-111\nAt
        least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
        number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
        Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can
        not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified
        for greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting
        presetId specified for greeting type [Introductory]. Custom greeting uploading
        method should be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds
        1000\n\n\n400\nAWR-136\nRing group with index 1 is not found\n\n\n400\nAWR-137\nRule
        index should be greater than 0\n\n\n400\nAWR-138\nContact center number cannot
        be used as called number\n\n\n400\nAWR-139\nHold audio interruption period
        not specified\n\n\n400\nAWR-140\nHold audio interruption period should be
        empty for interruption mode specified\n\n\n400\nAWR-144\nCall Queue agent
        with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not be used
        for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
        be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail
        or shared line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly
        user, voicemail, shared line group extension or current department can be
        a voicemail recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for
        call queue extension\n\n\n400\nAWR-177\nTime ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name]
        is too long: up to 127 symbols supported\n\n\n400\nCMN-101\nParameter [name]
        value is invalid\n\n\n400\nFPN-105\nNumber +16196093249 duplicates with company/extension
        direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [EditExtensions]
        permission\n\n\n403\nCMN-408\nIn order to call this API endpoint, user needs
        to have [EditUserAnsweringRules] permission for requested resource.\n\n\n404\nCMN-102\nResource
        for parameter [accountId] is not found"
      operationId: createAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Call
      - Handling
      - Rules
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