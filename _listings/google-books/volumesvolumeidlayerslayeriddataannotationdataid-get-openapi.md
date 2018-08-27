---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Get Annotation
  description: Gets the annotation data.
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
  /volumes/{volumeId}/layers/{layerId}/data/{annotationDataId}:
    get:
      summary: Get Annotation
      description: Gets the annotation data.
      operationId: books.layers.annotationData.get
      x-api-path-slug: volumesvolumeidlayerslayeriddataannotationdataid-get
      parameters:
      - in: query
        name: allowWebDefinitions
        description: For the dictionary layer
      - in: path
        name: annotationDataId
        description: The ID of the annotation data to retrieve
      - in: query
        name: contentVersion
        description: The content version for the volume you are trying to retrieve
      - in: query
        name: h
        description: The requested pixel height for any images
      - in: path
        name: layerId
        description: The ID for the layer to get the annotations
      - in: query
        name: locale
        description: The locale information for the data
      - in: query
        name: scale
        description: The requested scale for the image
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: path
        name: volumeId
        description: The volume to retrieve annotations for
      - in: query
        name: w
        description: The requested pixel width for any images
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