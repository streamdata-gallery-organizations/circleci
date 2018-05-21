---
name: CircleCI
x-slug: circleci
description: 'Velocity is critical for software teams in todays competitive landscape,
  but maintaining speed can be difficult as apps and systems grow larger and more
  complex. CircleCI&rsquo;s platform allows developers to rapidly release code (for
  web and mobile apps) they trust by automating the build, test, and deploy process.
  CircleCI enables developers to detect and fix bugs before they even reach customers.
  Thousands of leading companies including Facebook, Kickstarter, Shyp and Spotify
  rely on CircleCI to accelerate delivery of their code and enable developers to focus
  on creating business value fast. '
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: CircleCI
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/apis.md
specificationVersion: "0.14"
apis:
- name: CircleCI Get Me
  x-api-slug: circleci
  description: Provides information about the signed in user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//me
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/me-get-openapi.md
- name: CircleCI Get Project Username Project
  x-api-slug: circleci
  description: Build summary for each of the last 30 builds for a single git repo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}
  tags: Project, Username, Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameproject-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameproject-get-openapi.md
- name: CircleCI Parameters Project Username Project
  x-api-slug: circleci
  description: Parameters project username project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}
  tags: Parameters, Project, Username, Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameproject-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameproject-parameters-openapi.md
- name: CircleCI Add Project Username Project
  x-api-slug: circleci
  description: Triggers a new build, returns a summary of the build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}
  tags: Project, Username, Project
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameproject-post-openapi.md
- name: CircleCI Delete Project Username Project Build Cache
  x-api-slug: circleci
  description: Delete project username project build cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/build-cache
  tags: Project, Username, Project, Build, Cache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuildcache-delete-openapi.md
- name: CircleCI Parameters Project Username Project Build Cache
  x-api-slug: circleci
  description: Parameters project username project build cache.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/build-cache
  tags: Parameters, Project, Username, Project, Build, Cache
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuildcache-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuildcache-parameters-openapi.md
- name: CircleCI Get Project Username Project Checkout Key
  x-api-slug: circleci
  description: Get project username project checkout key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key
  tags: Project, Username, Project, Checkout, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkey-get-openapi.md
- name: CircleCI Parameters Project Username Project Checkout Key
  x-api-slug: circleci
  description: Parameters project username project checkout key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key
  tags: Parameters, Project, Username, Project, Checkout, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkey-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkey-parameters-openapi.md
- name: CircleCI Add Project Username Project Checkout Key
  x-api-slug: circleci
  description: |-
    Creates a new checkout key.
    Only usable with a user API token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key
  tags: Project, Username, Project, Checkout, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkey-post-openapi.md
- name: CircleCI Delete Project Username Project Checkout Key Fingerprint
  x-api-slug: circleci
  description: Delete project username project checkout key fingerprint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key/{fingerprint}
  tags: Project, Username, Project, Checkout, Key, Fingerprint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkeyfingerprint-delete-openapi.md
- name: CircleCI Get Project Username Project Checkout Key Fingerprint
  x-api-slug: circleci
  description: Get project username project checkout key fingerprint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key/{fingerprint}
  tags: Project, Username, Project, Checkout, Key, Fingerprint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkeyfingerprint-get-openapi.md
- name: CircleCI Parameters Project Username Project Checkout Key Fingerprint
  x-api-slug: circleci
  description: Parameters project username project checkout key fingerprint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/checkout-key/{fingerprint}
  tags: Parameters, Project, Username, Project, Checkout, Key, Fingerprint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkeyfingerprint-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectcheckoutkeyfingerprint-parameters-openapi.md
- name: CircleCI Get Project Username Project Envvar
  x-api-slug: circleci
  description: Lists the environment variables for :project
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar
  tags: Project, Username, Project, Envvar
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvar-get-openapi.md
- name: CircleCI Parameters Project Username Project Envvar
  x-api-slug: circleci
  description: Parameters project username project envvar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar
  tags: Parameters, Project, Username, Project, Envvar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvar-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvar-parameters-openapi.md
- name: CircleCI Add Project Username Project Envvar
  x-api-slug: circleci
  description: Add project username project envvar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar
  tags: Project, Username, Project, Envvar
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvar-post-openapi.md
- name: CircleCI Delete Project Username Project Envvar Name
  x-api-slug: circleci
  description: Deletes the environment variable named ':name'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar/{name}
  tags: Project, Username, Project, Envvar, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvarname-delete-openapi.md
- name: CircleCI Get Project Username Project Envvar Name
  x-api-slug: circleci
  description: Gets the hidden value of environment variable :name
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar/{name}
  tags: Project, Username, Project, Envvar, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvarname-get-openapi.md
- name: CircleCI Parameters Project Username Project Envvar Name
  x-api-slug: circleci
  description: Parameters project username project envvar name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/envvar/{name}
  tags: Parameters, Project, Username, Project, Envvar, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvarname-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectenvvarname-parameters-openapi.md
- name: CircleCI Parameters Project Username Project Ssh Key
  x-api-slug: circleci
  description: Parameters project username project ssh key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/ssh-key
  tags: Parameters, Project, Username, Project, Ssh, Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectsshkey-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectsshkey-parameters-openapi.md
- name: CircleCI Add Project Username Project Ssh Key
  x-api-slug: circleci
  description: Create an ssh key used to access external systems that require SSH
    key-based authentication
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/ssh-key
  tags: Project, Username, Project, Ssh, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectsshkey-post-openapi.md
- name: CircleCI Parameters Project Username Project Tree Branch
  x-api-slug: circleci
  description: Parameters project username project tree branch.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/tree/{branch}
  tags: Parameters, Project, Username, Project, Tree, Branch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojecttreebranch-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojecttreebranch-parameters-openapi.md
- name: CircleCI Add Project Username Project Tree Branch
  x-api-slug: circleci
  description: |-
    Triggers a new build, returns a summary of the build.
    Optional build parameters can be set using an experimental API.

    Note: For more about build parameters, read about [using parameterized builds](https://circleci.com/docs/parameterized-builds/)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/tree/{branch}
  tags: Project, Username, Project, Tree, Branch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojecttreebranch-post-openapi.md
- name: CircleCI Get Project Username Project Build Num
  x-api-slug: circleci
  description: |-
    Full details for a single build. The response includes all of the fields from the build summary.
    This is also the payload for the [notification webhooks](/docs/configuration/#notify), in which case this object is the value to a key named 'payload'.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}
  tags: Project, Username, Project, Build, Num
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-num-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num
  x-api-slug: circleci
  description: Parameters project username project build num.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}
  tags: Parameters, Project, Username, Project, Build, Num
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-num-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-num-parameters-openapi.md
- name: CircleCI Get Project Username Project Build Num Artifacts
  x-api-slug: circleci
  description: Get project username project build num artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/artifacts
  tags: Project, Username, Project, Build, Num, Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numartifacts-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Artifacts
  x-api-slug: circleci
  description: Parameters project username project build num artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/artifacts
  tags: Parameters, Project, Username, Project, Build, Num, Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numartifacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numartifacts-parameters-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Cancel
  x-api-slug: circleci
  description: Parameters project username project build num cancel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/cancel
  tags: Parameters, Project, Username, Project, Build, Num, Cancel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numcancel-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numcancel-parameters-openapi.md
- name: CircleCI Add Project Username Project Build Num Cancel
  x-api-slug: circleci
  description: Cancels the build, returns a summary of the build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/cancel
  tags: Project, Username, Project, Build, Num, Cancel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numcancel-post-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Retry
  x-api-slug: circleci
  description: Parameters project username project build num retry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/retry
  tags: Parameters, Project, Username, Project, Build, Num, Retry
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numretry-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numretry-parameters-openapi.md
- name: CircleCI Add Project Username Project Build Num Retry
  x-api-slug: circleci
  description: Retries the build, returns a summary of the new build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/retry
  tags: Project, Username, Project, Build, Num, Retry
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numretry-post-openapi.md
- name: CircleCI Get Project Username Project Build Num Tests
  x-api-slug: circleci
  description: |-
    Provides test metadata for a build
    Note: [Learn how to set up your builds to collect test metadata](https://circleci.com/docs/test-metadata/)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/tests
  tags: Project, Username, Project, Build, Num, Tests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numtests-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Tests
  x-api-slug: circleci
  description: Parameters project username project build num tests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/tests
  tags: Parameters, Project, Username, Project, Build, Num, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numtests-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projectusernameprojectbuild-numtests-parameters-openapi.md
- name: CircleCI Get Projects
  x-api-slug: circleci
  description: List of all the projects you're following on CircleCI, with build information
    organized by branch.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//projects
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projects-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/projects-get-openapi.md
- name: CircleCI Get Recent Builds
  x-api-slug: circleci
  description: Build summary for each of the last 30 recent builds, ordered by build_num.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//recent-builds
  tags: Recent, Builds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/recentbuilds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/recentbuilds-get-openapi.md
- name: CircleCI Add User Heroku Key
  x-api-slug: circleci
  description: Adds your Heroku API key to CircleCI, takes apikey as form param name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1//user/heroku-key
  tags: User, Heroku, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/userherokukey-post-openapi.md
- name: CircleCI
  x-api-slug: circleci
  description: 'Velocity is critical for software teams in todays competitive landscape,
    but maintaining speed can be difficult as apps and systems grow larger and more
    complex. CircleCI&rsquo;s platform allows developers to rapidly release code (for
    web and mobile apps) they trust by automating the build, test, and deploy process.
    CircleCI enables developers to detect and fix bugs before they even reach customers.
    Thousands of leading companies including Facebook, Kickstarter, Shyp and Spotify
    rely on CircleCI to accelerate delivery of their code and enable developers to
    focus on creating business value fast. '
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/circleci-logo.png
  humanURL: https://circleci.com/
  baseURL: https://circleci.com//api/v1
  tags: CircleCI
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/circleci/master/_listings/circleci/openapi.md
x-common:
- type: x-blog
  url: https://circleci.com/blog/
- type: x-blog-rss
  url: https://circleci.com/blog/feed.xml
- type: x-case-studies
  url: https://circleci.com/customers/
- type: x-change-log
  url: https://circleci.com/changelog/
- type: x-contact-form
  url: https://circleci.com/contact/
- type: x-documentation
  url: https://circleci.com/docs/
- type: x-github
  url: https://github.com/circleci
- type: x-linkedin
  url: https://www.linkedin.com/company/circleci
- type: x-pricing
  url: https://circleci.com/pricing/
- type: x-privacy-policy
  url: https://circleci.com/privacy/
- type: x-selfservice-registration
  url: https://circleci.com/signup/
- type: x-status
  url: https://status.circleci.com/
- type: x-support
  url: https://support.circleci.com/hc/en-us
- type: x-terms-of-service
  url: https://circleci.com/terms-of-service/
- type: x-twitter
  url: https://twitter.com/circleci
- type: x-website
  url: https://circleci.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---