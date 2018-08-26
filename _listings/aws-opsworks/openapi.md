---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeMyUserProfile:
    get:
      summary: Describe My User Profile
      description: Describes a user's SSH information.
      operationId: describeMyUserProfile
      x-api-path-slug: actiondescribemyuserprofile-get
      parameters:
      - in: query
        name: UserProfile
        description: A UserProfile object that describes the users SSH information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - My
      - User
      - Profile
  /?Action=UpdateMyUserProfile:
    get:
      summary: Update My User Profile
      description: Updates a user's SSH public key.
      operationId: updateMyUserProfile
      x-api-path-slug: actionupdatemyuserprofile-get
      parameters:
      - in: query
        name: SshPublicKey
        description: The users SSH public key
        type: string
      responses:
        200:
          description: OK
      tags:
      - My
      - User
      - Profile
---