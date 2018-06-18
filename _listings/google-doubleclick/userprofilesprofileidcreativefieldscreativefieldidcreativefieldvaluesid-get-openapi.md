---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API UpGetdate Creative Field Value
  version: 1.0.0
  description: Gets one creative field value by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/creativeFields:
    get:
      summary: Get Creative Fields
      description: Retrieves a list of creative fields, possibly filtered. This method
        supports paging.
      operationId: dfareporting.creativeFields.list
      x-api-path-slug: userprofilesprofileidcreativefields-get
      parameters:
      - in: query
        name: advertiserIds
        description: Select only creative fields that belong to these advertisers
      - in: query
        name: ids
        description: Select only creative fields with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for creative fields by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    patch:
      summary: Update Creative Fields
      description: Updates an existing creative field. This method supports patch
        semantics.
      operationId: dfareporting.creativeFields.patch
      x-api-path-slug: userprofilesprofileidcreativefields-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Creative Field ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    post:
      summary: Create Creative Fields
      description: Inserts a new creative field.
      operationId: dfareporting.creativeFields.insert
      x-api-path-slug: userprofilesprofileidcreativefields-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    put:
      summary: Update Creative Fields
      description: Updates an existing creative field.
      operationId: dfareporting.creativeFields.update
      x-api-path-slug: userprofilesprofileidcreativefields-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
  /userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues:
    get:
      summary: Get Creative Field Values
      description: Retrieves a list of creative field values, possibly filtered. This
        method supports paging.
      operationId: dfareporting.creativeFieldValues.list
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-get
      parameters:
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: query
        name: ids
        description: Select only creative field values with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for creative field values by their values
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    patch:
      summary: Update Creative Field Value
      description: Updates an existing creative field value. This method supports
        patch semantics.
      operationId: dfareporting.creativeFieldValues.patch
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: query
        name: id
        description: Creative Field Value ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    post:
      summary: Insert Creative Field Value
      description: Inserts a new creative field value.
      operationId: dfareporting.creativeFieldValues.insert
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    put:
      summary: Update Creative Field Value
      description: Updates an existing creative field value.
      operationId: dfareporting.creativeFieldValues.update
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvalues-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
  /userprofiles/{profileId}/creativeFields/{creativeFieldId}/creativeFieldValues/{id}:
    delete:
      summary: Delete Creative Field Value
      description: Deletes an existing creative field value.
      operationId: dfareporting.creativeFieldValues.delete
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-delete
      parameters:
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: path
        name: id
        description: Creative Field Value ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
    get:
      summary: UpGetdate Creative Field Value
      description: Gets one creative field value by ID.
      operationId: dfareporting.creativeFieldValues.get
      x-api-path-slug: userprofilesprofileidcreativefieldscreativefieldidcreativefieldvaluesid-get
      parameters:
      - in: path
        name: creativeFieldId
        description: Creative field ID for this creative field value
      - in: path
        name: id
        description: Creative Field Value ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Creative Field
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