---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Get Accounts
  description: Lists the sub-accounts in your Merchant Center account. This method
    can only be called for multi-client accounts.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{merchantId}/accounts:
    get:
      summary: Get Accounts
      description: Lists the sub-accounts in your Merchant Center account. This method
        can only be called for multi-client accounts.
      operationId: content.accounts.list
      x-api-path-slug: merchantidaccounts-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of accounts to return in the response, used
          for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Accounts
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