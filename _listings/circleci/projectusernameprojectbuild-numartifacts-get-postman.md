{
  "info": {
    "name": "CircleCI",
    "_postman_id": "52f2c571-96cd-43cb-aba2-f2153cc6f866",
    "description": "The CircleCI API is a RESTful, fully-featured API that allows you to do almost anything in CircleCI. You can access all information and trigger all actions. The only thing we don&rsquo;t provide access to is billing functions, which must be done from the CircleCI web UI.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "project",
      "item": [
        {
          "id": "d1060534-203d-4b20-8c5f-ea5616e64003",
          "name": "getProjectUsernameProjectBuildNumArtifacts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "circleci.com",
              "path": [
                "api",
                "v1",
                "project/:username/:project/:build_num/artifacts"
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "username",
                  "type": "string"
                },
                {
                  "id": "project",
                  "value": "project",
                  "type": "string"
                },
                {
                  "id": "build_num",
                  "value": "build_num",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get project username project build num artifacts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "500af41b-cadf-4a02-9851-5da0042a0b4c"
            }
          ]
        }
      ]
    }
  ]
}