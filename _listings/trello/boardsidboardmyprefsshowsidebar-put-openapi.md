---
swagger: "2.0"
x-collection-name: Trello
x-complete: 0
info:
  title: Trello Put Boards My Preferences Show Sidebar
  description: Put boards my preferences show sidebar.
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /boards/{idBoard}/myPrefs:
    get:
      summary: Get Boards My Preferences
      description: Get boards my preferences.
      operationId: getBoardsMyPrefsByIdBoard
      x-api-path-slug: boardsidboardmyprefs-get
      parameters:
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - My
      - Preferences
  /boards/{idBoard}/myPrefs/emailPosition:
    put:
      summary: Put Boards My Preferences Emailposition
      description: Put boards my preferences emailposition.
      operationId: updateBoardsMyPrefsEmailPositionByIdBoard
      x-api-path-slug: boardsidboardmyprefsemailposition-put
      parameters:
      - in: body
        name: body
        description: Attributes of My Prefs Email Position to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - My
      - Preferences
      - Emailposition
  /boards/{idBoard}/myPrefs/idEmailList:
    put:
      summary: Put Boards My Preferences Emaillist
      description: Put boards my preferences emaillist.
      operationId: updateBoardsMyPrefsIdEmailListByIdBoard
      x-api-path-slug: boardsidboardmyprefsidemaillist-put
      parameters:
      - in: body
        name: body
        description: Attributes of My Prefs Id Email List to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - My
      - Preferences
      - Emaillist
  /boards/{idBoard}/myPrefs/showListGuide:
    put:
      summary: Put Boards My Preferences Showlistgue
      description: Put boards my preferences showlistgue.
      operationId: updateBoardsMyPrefsShowListGuideByIdBoard
      x-api-path-slug: boardsidboardmyprefsshowlistguide-put
      parameters:
      - in: body
        name: body
        description: Attributes of My Prefs Show List Guide to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - My
      - Preferences
      - Showlistgue
  /boards/{idBoard}/myPrefs/showSidebar:
    put:
      summary: Put Boards My Preferences Show Sidebar
      description: Put boards my preferences show sidebar.
      operationId: updateBoardsMyPrefsShowSidebarByIdBoard
      x-api-path-slug: boardsidboardmyprefsshowsidebar-put
      parameters:
      - in: body
        name: body
        description: Attributes of My Prefs Show Sidebar to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idBoard
        description: board_id
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Boards
      - My
      - Preferences
      - Show
      - Sidebar
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