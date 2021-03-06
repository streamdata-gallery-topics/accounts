---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 0
info:
  title: Quovo Get a user's manual accounts
  description: Returns all Manual Portfolios of a given User.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /connections/{connection_id}/accounts:
    get:
      summary: Fetch the Connection's Accounts
      description: |-
        Fetches all of the accounts belonging to the connection. These are automatically created by Quovo after an initial sync.

        If you have a Postman Environment set up, this request will automatically set the variable `account_id` to the id of the first account returned.
      operationId: ConnectionsAccountsByConnectionIdGet4
      x-api-path-slug: connectionsconnection-idaccounts-get
      parameters:
      - in: path
        name: connection_id
      responses:
        200:
          description: OK
      tags:
      - Fetch
      - Connections
      - Accounts
  /accounts/{account_id}/holdings:
    get:
      summary: Get an account's holdings
      description: Fetches all holdings for a specific account.
      operationId: AccountsHoldingsByAccountIdGet
      x-api-path-slug: accountsaccount-idholdings-get
      parameters:
      - in: path
        name: account_id
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Holdings
  /accounts/{account_id}/extras:
    get:
      summary: Fetch an Account's Extras Information
      description: Retrieves an Account's Extras Information.
      operationId: AccountsExtrasByAccountIdGet
      x-api-path-slug: accountsaccount-idextras-get
      parameters:
      - in: path
        name: account_id
      responses:
        200:
          description: OK
      tags:
      - Fetch
      - Accounts
      - Extras
      - Information
  /manual_accounts/{manual_account_id}/manual_holdings:
    get:
      summary: Get a manual account's holdings
      description: Fetches all of the Portfolio's Manual Assets.
      operationId: ManualAccountsManualHoldingsByManualAccountIdGet
      x-api-path-slug: manual-accountsmanual-account-idmanual-holdings-get
      parameters:
      - in: path
        name: manual_account_id
      responses:
        200:
          description: OK
      tags:
      - Manual
      - Accounts
      - Holdings
  /users/{user_id}/manual_accounts:
    get:
      summary: Get a user's manual accounts
      description: Returns all Manual Portfolios of a given User.
      operationId: UsersManualAccountsByUserIdGet
      x-api-path-slug: usersuser-idmanual-accounts-get
      parameters:
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Manual
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