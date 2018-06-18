---
name: Google Books
x-slug: google-books
description: Google Books is our effort to make book content more discoverable on
  the Web. Using the Google Books API, your application can perform full-text searches
  and retrieve book information, viewability and eBook availability. You can also
  manage your personal bookshelves.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2017-03-16 at 4.28.26 PM.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Annotation
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/apis.md
specificationVersion: "0.14"
apis:
- name: Google Books API Get Annotations
  x-api-slug: google-books-api
  description: Retrieves a list of annotations, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/mylibraryannotations-get-openapi.md
- name: Google Books API insert Annotation
  x-api-slug: google-books-api
  description: Inserts a new annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/mylibraryannotations-post-openapi.md
- name: Google Books API Get Annotation
  x-api-slug: google-books-api
  description: Gets the summary of specified layers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/summary
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/mylibraryannotationssummary-post-openapi.md
- name: Google Books API Delete Annotation
  x-api-slug: google-books-api
  description: Deletes an annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/mylibraryannotationsannotationid-delete-openapi.md
- name: Google Books API Update Annotation
  x-api-slug: google-books-api
  description: Updates an existing annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/mylibraryannotationsannotationid-put-openapi.md
- name: Google Books API Get Volume Annotations
  x-api-slug: google-books-api
  description: Gets the volume annotations for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/volumesvolumeidlayerslayerid-get-openapi.md
- name: Google Books API Get Volume Annotion
  x-api-slug: google-books-api
  description: Gets the volume annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/volumesvolumeidlayerslayeridannotationsannotationid-get-openapi.md
- name: Google Books API Get Annotations
  x-api-slug: google-books-api
  description: Gets the annotation data for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/data
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/volumesvolumeidlayerslayeriddata-get-openapi.md
- name: Google Books API Get Annotation
  x-api-slug: google-books-api
  description: Gets the annotation data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/data/{annotationDataId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/volumesvolumeidlayerslayeriddataannotationdataid-get-openapi.md
- name: Google Books API
  x-api-slug: google-books-api
  description: The APIs in the Google Books API Family let you bringGoogle Booksfeatures
    to your site or application. The newGoogle Books APIlets you perform programmatically
    most of the operations that you can do interactively on the Google Books website.
    TheEmbedded Viewer APIlets you embed the content directly into your site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/annotation/master/_listings/google-books/openapi.md
x-common:
- type: x-blog
  url: http://booksearch.blogspot.com
- type: x-blog-rss
  url: http://booksearch.blogspot.com/feeds/posts/default?alt=rss
- type: x-branding-guidelines
  url: https://developers.google.com/books/branding
- type: x-code
  url: https://developers.google.com/books/docs/v1/libraries
- type: x-documentation
  url: https://developers.google.com/books/docs/overview
- type: x-embeddable
  url: https://developers.google.com/books/docs/viewer/developers_guide
- type: x-partners
  url: https://books.google.com/intl/en/googlebooks/partners/
- type: x-privacy-policy
  url: https://books.google.com/intl/en/policies/privacy/
- type: x-terms-of-service
  url: https://developers.google.com/books/terms.html
- type: x-website
  url: https://developers.google.com/books/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---