---
name: Google Doubleclick
x-slug: google-doubleclick
description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
  to access and update account information and to submit creatives. The API also allows
  an application (whether it does static bidding or real-time bidding) to discover
  direct deals that sellers make available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Creative Field
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/apis.md
specificationVersion: "0.14"
apis:
- name: Google Doubleclick API Get Creative Fields
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of creative fields, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-get-openapi.md
- name: Google Doubleclick API Update Creative Fields
  x-api-slug: google-doubleclick-api
  description: Updates an existing creative field. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-patch-openapi.md
- name: Google Doubleclick API Create Creative Fields
  x-api-slug: google-doubleclick-api
  description: Inserts a new creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-post-openapi.md
- name: Google Doubleclick API Update Creative Fields
  x-api-slug: google-doubleclick-api
  description: Updates an existing creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefields-put-openapi.md
- name: Google Doubleclick API Get Creative Field Values
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of creative field values, possibly filtered. This
    method supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-get-openapi.md
- name: Google Doubleclick API Update Creative Field Value
  x-api-slug: google-doubleclick-api
  description: Updates an existing creative field value. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-patch-openapi.md
- name: Google Doubleclick API Insert Creative Field Value
  x-api-slug: google-doubleclick-api
  description: Inserts a new creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-post-openapi.md
- name: Google Doubleclick API Update Creative Field Value
  x-api-slug: google-doubleclick-api
  description: Updates an existing creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-put-openapi.md
- name: Google Doubleclick API Delete Creative Field Value
  x-api-slug: google-doubleclick-api
  description: Deletes an existing creative field value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues/{id}
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-delete-openapi.md
- name: Google Doubleclick API UpGetdate Creative Field Value
  x-api-slug: google-doubleclick-api
  description: Gets one creative field value by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues/{id}
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-get-openapi.md
- name: Google Doubleclick API Delete Creative Field
  x-api-slug: google-doubleclick-api
  description: Deletes an existing creative field.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{id}
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldsid-delete-openapi.md
- name: Google Doubleclick API Get Creative Field
  x-api-slug: google-doubleclick-api
  description: Gets one creative field by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/creativeFields/{id}
  tags: Advertising,Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/userprofilesprofileidcreativefieldsid-get-openapi.md
- name: Google Doubleclick API
  x-api-slug: google-doubleclick-api
  description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
    to access and update account information and to submit creatives. The API also
    allows an application (whether it does static bidding or real-time bidding) to
    discover direct deals that sellers make available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Creative Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/creative-field/master/_listings/google-doubleclick/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/ad-exchange/buyer-rest/auth-guide
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/ad_exchange
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/ad-exchange/buyer-rest/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-doubleclick-ad-exchange-buyer-api
- type: x-getting-started
  url: https://developers.google.com/ad-exchange/buyer-rest/start
- type: x-support
  url: https://developers.google.com/ad-exchange/buyer-rest/community/
- type: x-website
  url: https://www.doubleclickbygoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---