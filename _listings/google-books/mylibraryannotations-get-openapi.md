---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Get Annotations
  description: Retrieves a list of annotations, possibly filtered.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mylibrary/annotations:
    get:
      summary: Get Annotations
      description: Retrieves a list of annotations, possibly filtered.
      operationId: books.mylibrary.annotations.list
      x-api-path-slug: mylibraryannotations-get
      parameters:
      - in: query
        name: contentVersion
        description: The content version for the requested volume
      - in: query
        name: layerId
        description: The layer ID to limit annotation by
      - in: query
        name: layerIds
        description: The layer ID(s) to limit annotation by
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: The value of the nextToken from the previous page
      - in: query
        name: showDeleted
        description: Set to true to return deleted annotations
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: updatedMax
        description: RFC 3339 timestamp to restrict to items updated prior to this
          timestamp (exclusive)
      - in: query
        name: updatedMin
        description: RFC 3339 timestamp to restrict to items updated since this timestamp
          (inclusive)
      - in: query
        name: volumeId
        description: The volume to restrict annotations to
      responses:
        200:
          description: OK
      tags:
      - Annotation
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