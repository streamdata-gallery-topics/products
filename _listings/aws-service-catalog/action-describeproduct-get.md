---
swagger: "2.0"
info:
  title: AWS Service Catalog API Describe Product
  version: 1.0.0
  description: Retrieves information about a specified product.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeProduct:
    get:
      summary: ' Describe Product '
      description: Retrieves information about a specified product
      operationId: describeProduct
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - products
definitions: []
x-collection-name: AWS Service Catalog
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