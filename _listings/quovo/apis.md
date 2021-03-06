---
name: Quovo
x-slug: quovo
description: Quovo&rsquo;s API provides methods for retrieving data from financial
  institutions on behalf of clients, advisors, and other users. This documentation
  includes detailed explanations of API endpoints and common data definitions. Please
  note that this documentation does not list all API endpoints. Additionally, you
  may not have access to all of the listed endpoints depending on the services you&rsquo;ve
  purchased from Quovo.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
x-kinRank: "7"
x-alexaRank: "391003"
tags: Accounts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/apis.md
specificationVersion: "0.14"
apis:
- name: Quovo API v3 - Fetch the Connection's Accounts
  x-api-slug: connectionsconnection-idaccounts-get
  description: |-
    Fetches all of the accounts belonging to the connection. These are automatically created by Quovo after an initial sync.

    If you have a Postman Environment set up, this request will automatically set the variable `account_id` to the id of the first account returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/connectionsconnection-idaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/connectionsconnection-idaccounts-get-openapi.md
- name: Quovo API v3 - Get an account's holdings
  x-api-slug: accountsaccount-idholdings-get
  description: Fetches all holdings for a specific account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idholdings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idholdings-get-openapi.md
- name: Quovo API v3 - Fetch an Account's Extras Information
  x-api-slug: accountsaccount-idextras-get
  description: Retrieves an Account's Extras Information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idextras-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idextras-get-openapi.md
- name: Quovo API v3 - Get a manual account's holdings
  x-api-slug: manual-accountsmanual-account-idmanual-holdings-get
  description: Fetches all of the Portfolio's Manual Assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-idmanual-holdings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-idmanual-holdings-get-openapi.md
- name: Quovo API v3 - Get a user's manual accounts
  x-api-slug: usersuser-idmanual-accounts-get
  description: Returns all Manual Portfolios of a given User.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-get-openapi.md
- name: Quovo API v3 - Get an account's transactions
  x-api-slug: accountsaccount-idtransactions-get
  description: Provides information on an account's historical transactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idtransactions-get-openapi.md
- name: Quovo API v3 - Get all manual accounts
  x-api-slug: manual-accounts-get
  description: Retrieves all Manual Accounts across all Users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accounts-get-openapi.md
- name: Quovo API v3 - Get all accounts
  x-api-slug: accounts-get
  description: Fetches all Accounts accross all Users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-openapi.md
- name: Quovo API v3 - Get a user's accounts
  x-api-slug: usersuser-idaccounts-get
  description: Fetches all Accounts for a specific user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idaccounts-get-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
- name: Quovo API v3 - Update a manual account
  x-api-slug: manual-accountsmanual-account-id-put
  description: Modifies a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-put-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
- name: Quovo API v3 - Update a manual account
  x-api-slug: manual-accountsmanual-account-id-put
  description: Modifies a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-put-openapi.md
- name: Quovo API v3 - Update a manual account
  x-api-slug: manual-accountsmanual-account-id-put
  description: Modifies a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-put-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Get all accounts
  x-api-slug: accounts-get
  description: Fetches all Accounts accross all Users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-openapi.md
- name: Quovo API v3 - Get all accounts
  x-api-slug: accounts-get
  description: Fetches all Accounts accross all Users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accounts-get-openapi.md
- name: Quovo API v3 - Fetch an Account's Extras Information
  x-api-slug: accountsaccount-idextras-get
  description: Retrieves an Account's Extras Information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idextras-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idextras-get-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Update an account
  x-api-slug: accountsaccount-id-put
  description: Modifies an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-put-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Get a single account
  x-api-slug: accountsaccount-id-get
  description: Provides information on a single account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-id-get-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Get auth for an account
  x-api-slug: accountsaccount-idauth-get
  description: Retrieves all authentication information associated with an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/accountsaccount-idauth-get-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Create a manual account
  x-api-slug: usersuser-idmanual-accounts-post
  description: Creates a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/usersuser-idmanual-accounts-post-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Delete a manual account
  x-api-slug: manual-accountsmanual-account-id-delete
  description: Deletes a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-delete-openapi.md
- name: Quovo API v3 - Update a manual account
  x-api-slug: manual-accountsmanual-account-id-put
  description: Modifies a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-put-openapi.md
- name: Quovo API v3 - Update a manual account
  x-api-slug: manual-accountsmanual-account-id-put
  description: Modifies a Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-put-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
- name: Quovo API v3 - Get a single manual account
  x-api-slug: manual-accountsmanual-account-id-get
  description: Returns a single Manual Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accounts/master/_listings/quovo/manual-accountsmanual-account-id-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.quovo.com/fintech-blog/feed/
- type: x-postman-collection
  url: https://www.getpostman.com/collections/82cf673bb22d4f8b8881
- type: x-website
  url: http://quovo.com
- type: x-api-gallery
  url: http://quandl.api.gallery.streamdata.io
- type: x-api-stack
  url: http://quovo.stack.network
- type: x-authentication
  url: https://api.quovo.com/docs/v3/#authentication
- type: x-blog
  url: https://www.quovo.com/fintech-blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/quovo
- type: x-developer
  url: https://api.quovo.com/docs/v3/
- type: x-email
  url: audit@quovo.com
- type: x-email
  url: info@quovo.com
- type: x-email
  url: copyright@quovo.com
- type: x-email
  url: support@quovo.com
- type: x-github
  url: https://github.com/quovo
- type: x-twitter
  url: https://twitter.com/quovo
- type: x-webhook
  url: https://api.quovo.com/docs/v3/#webhooks
- type: x-website
  url: https://www.quovo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---