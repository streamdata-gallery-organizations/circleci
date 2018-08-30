{
  "info": {
    "name": "CircleCI Get Project Username Project",
    "_postman_id": "e8f824cd-4a11-4f7f-b566-93259209f87f",
    "description": "Build summary for each of the last 30 builds for a single git repo.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Me",
      "item": [
        {
          "id": "328d24c8-01b7-43df-94ef-afa0ca0118a4",
          "name": "getMe",
          "request": {
            "url": "http://circleci.com/api/v1/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about the signed in user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fa3cd0f-a7dc-4650-85b6-9319ef811509"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "89a6b2c3-7fb2-4bcb-84d3-2666cc9797d8",
          "name": "getProjectUsernameProject",
          "request": {
            "url": {
              "protocol": "http",
              "host": "circleci.com",
              "path": [
                "api",
                "v1",
                "project/:username/:project"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Build summary for each of the last 30 builds for a single git repo."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbc299b8-7230-4e69-8993-285267d32194"
            }
          ]
        }
      ]
    }
  ]
}