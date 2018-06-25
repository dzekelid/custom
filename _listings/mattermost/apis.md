---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Create a custom emoji
  x-api-slug: mattermost-api
  description: |-
    Create a custom emoji for the team.
    ##### Permissions
    Must be authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji
  tags: Custom,Emoji
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emoji-post-openapi.md
- name: Mattermost API Get a list of custom emoji
  x-api-slug: mattermost-api
  description: |-
    Get a page of metadata for custom emoji on the system. Since server version 4.7, sort using the `sort` query parameter.
    ##### Permissions
    Must be authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji
  tags: List,Of,Custom,Emoji
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emoji-get-openapi.md
- name: Mattermost API Get a custom emoji
  x-api-slug: mattermost-api
  description: |-
    Get some metadata for a custom emoji.
    ##### Permissions
    Must be authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/{emoji_id}
  tags: Custom,Emoji
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojiemoji-id-get-openapi.md
- name: Mattermost API Delete a custom emoji
  x-api-slug: mattermost-api
  description: |-
    Delete a custom emoji.
    ##### Permissions
    Must have the `manage_team` or `manage_system` permissions or be the user who created the emoji.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/{emoji_id}
  tags: Custom,Emoji
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojiemoji-id-delete-openapi.md
- name: Mattermost API Get a custom emoji by name
  x-api-slug: mattermost-api
  description: |-
    Get some metadata for a custom emoji using its name.
    ##### Permissions
    Must be authenticated.

    __Minimum server version__: 4.7
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/name/{emoji_name}
  tags: Custom,Emoji,By,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojinameemoji-name-get-openapi.md
- name: Mattermost API Get custom emoji image
  x-api-slug: mattermost-api
  description: |-
    Get the image for a custom emoji.
    ##### Permissions
    Must be authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/{emoji_id}/image
  tags: Custom,Emoji,Image
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojiemoji-idimage-get-openapi.md
- name: Mattermost API Search custom emoji
  x-api-slug: mattermost-api
  description: |-
    Search for custom emoji by name based on search criteria provided in the request body. A maximum of 200 results are returned.
    ##### Permissions
    Must be authenticated.

    __Minimum server version__: 4.7
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/search
  tags: Search,Custom,Emoji
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojisearch-post-openapi.md
- name: Mattermost API Autocomplete custom emoji
  x-api-slug: mattermost-api
  description: |-
    Get a list of custom emoji with names starting with or matching the provided name. Returns a maximum of 100 results.
    ##### Permissions
    Must be authenticated.

    __Minimum server version__: 4.7
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/autocomplete
  tags: Autocomplete,Custom,Emoji
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojiautocomplete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/emojiautocomplete-get-openapi.md
- name: Mattermost API
  x-api-slug: mattermost-api
  description: Open source, private cloud Slack-alternative, Workplace messaging for
    web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
    configurable, and scalable from teams to the enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/mattermost/openapi.md
x-common:
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---