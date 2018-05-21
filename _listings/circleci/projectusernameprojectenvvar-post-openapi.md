---
swagger: "2.0"
x-collection-name: CircleCI
x-complete: 0
info:
  title: CircleCI Add Project Username Project Envvar
  description: Add project username project envvar.
  version: 1.0.0
host: circleci.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Get Me
      description: Provides information about the signed in user.
      operationId: getMe
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me
  /project/{username}/{project}:
    get:
      summary: Get Project Username Project
      description: Build summary for each of the last 30 builds for a single git repo.
      operationId: getProjectUsernameProject
      x-api-path-slug: projectusernameproject-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
    parameters:
      summary: Parameters Project Username Project
      description: Parameters project username project.
      operationId: parametersProjectUsernameProject
      x-api-path-slug: projectusernameproject-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
    post:
      summary: Add Project Username Project
      description: Triggers a new build, returns a summary of the build.
      operationId: postProjectUsernameProject
      x-api-path-slug: projectusernameproject-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
  /project/{username}/{project}/build-cache:
    delete:
      summary: Delete Project Username Project Build Cache
      description: Delete project username project build cache.
      operationId: deleteProjectUsernameProjectBuildCache
      x-api-path-slug: projectusernameprojectbuildcache-delete
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Build
      - Cache
    parameters:
      summary: Parameters Project Username Project Build Cache
      description: Parameters project username project build cache.
      operationId: parametersProjectUsernameProjectBuildCache
      x-api-path-slug: projectusernameprojectbuildcache-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Build
      - Cache
  /project/{username}/{project}/checkout-key:
    get:
      summary: Get Project Username Project Checkout Key
      description: Get project username project checkout key.
      operationId: getProjectUsernameProjectCheckoutKey
      x-api-path-slug: projectusernameprojectcheckoutkey-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Checkout
      - Key
    parameters:
      summary: Parameters Project Username Project Checkout Key
      description: Parameters project username project checkout key.
      operationId: parametersProjectUsernameProjectCheckoutKey
      x-api-path-slug: projectusernameprojectcheckoutkey-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Checkout
      - Key
    post:
      summary: Add Project Username Project Checkout Key
      description: |-
        Creates a new checkout key.
        Only usable with a user API token.
      operationId: postProjectUsernameProjectCheckoutKey
      x-api-path-slug: projectusernameprojectcheckoutkey-post
      parameters:
      - in: body
        name: type
        description: The type of key to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Checkout
      - Key
  /project/{username}/{project}/checkout-key/{fingerprint}:
    delete:
      summary: Delete Project Username Project Checkout Key Fingerprint
      description: Delete project username project checkout key fingerprint.
      operationId: deleteProjectUsernameProjectCheckoutKeyFingerprint
      x-api-path-slug: projectusernameprojectcheckoutkeyfingerprint-delete
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Checkout
      - Key
      - Fingerprint
    get:
      summary: Get Project Username Project Checkout Key Fingerprint
      description: Get project username project checkout key fingerprint.
      operationId: getProjectUsernameProjectCheckoutKeyFingerprint
      x-api-path-slug: projectusernameprojectcheckoutkeyfingerprint-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Checkout
      - Key
      - Fingerprint
    parameters:
      summary: Parameters Project Username Project Checkout Key Fingerprint
      description: Parameters project username project checkout key fingerprint.
      operationId: parametersProjectUsernameProjectCheckoutKeyFingerprint
      x-api-path-slug: projectusernameprojectcheckoutkeyfingerprint-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Checkout
      - Key
      - Fingerprint
  /project/{username}/{project}/envvar:
    get:
      summary: Get Project Username Project Envvar
      description: Lists the environment variables for :project
      operationId: getProjectUsernameProjectEnvvar
      x-api-path-slug: projectusernameprojectenvvar-get
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Envvar
    parameters:
      summary: Parameters Project Username Project Envvar
      description: Parameters project username project envvar.
      operationId: parametersProjectUsernameProjectEnvvar
      x-api-path-slug: projectusernameprojectenvvar-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Project
      - Username
      - Project
      - Envvar
    post:
      summary: Add Project Username Project Envvar
      description: Add project username project envvar.
      operationId: postProjectUsernameProjectEnvvar
      x-api-path-slug: projectusernameprojectenvvar-post
      responses:
        200:
          description: OK
      tags:
      - Project
      - Username
      - Project
      - Envvar
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