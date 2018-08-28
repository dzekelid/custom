---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Custom
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Company Greeting
  x-api-slug: restapiv1-0accountaccountidgreeting-post
  description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid attachment
    media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not applicable to company
    rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create User Custom Greeting
  x-api-slug: restapiv1-0accountaccountidextensionextensionidgreeting-post
  description: "Creates custom greeting for an extension user.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nHeavy\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-128\nAttachment
    body is empty\n\n\n400\nAWR-129\nInvalid attachment media type\n\n\n400\nAWR-165\nHold
    music can be set for business hours rule only: the same value will be applied
    to all rules\n\n\n400\nCLR-103\nCompany level greeting cannot be created on user
    level.\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found\n\n\n400\nCMN-111\nBusiness operation
    is not supported"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Custom Greeting Info
  x-api-slug: restapiv1-0accountaccountidextensionextensionidgreetinggreetingid-get
  description: "Returns a custom user greeting by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n404\nCMN-102\nResource for parameter
    [greetingId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgreetinggreetingid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidgreetinggreetingid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - [Beta] Get Call Recording Custom
    Greetings
  x-api-slug: restapiv1-0accountaccountidcallrecordingcustomgreetings-get
  description: |-
    Returns call recording custom greetings.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyInfo
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/ringcentral/restapiv1-0accountaccountidcallrecordingcustomgreetings-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---