---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get User Accounts
  description: The Facebook apps and pages owned by the current user
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{application}/accounts:
    get:
      summary: Get Application Accounts
      description: Test User accounts associated with the application.
      operationId: getApplicationAccounts
      x-api-path-slug: applicationaccounts-get
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Accounts
  /{application}/accounts/test-users:
    post:
      summary: Post Application Accounts Test Users
      description: Creates a test account for the application
      operationId: postApplicationAccountsTestUsers
      x-api-path-slug: applicationaccountstestusers-post
      parameters:
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: installed
        description: Install app for the test user upon creation
      - in: query
        name: name
        description: A name for the test user
      - in: query
        name: permissions
        description: List of extended permissions app granted for the new test user
          if installed is true
      responses:
        200:
          description: OK
      tags:
      - Application
      - Accounts
      - Test
      - Users
  /{user}/accounts:
    get:
      summary: Get User Accounts
      description: The Facebook apps and pages owned by the current user
      operationId: getUserAccounts
      x-api-path-slug: useraccounts-get
      parameters:
      - in: path
        name: user
        description: Represents the ID of the user object
      responses:
        200:
          description: OK
      tags:
      - User
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