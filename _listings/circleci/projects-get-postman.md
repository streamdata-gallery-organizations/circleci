{
  "info": {
    "name": "CircleCI Get Projects",
    "_postman_id": "da8dab5e-5530-4d5e-908f-09807b9efec8",
    "description": "List of all the projects you're following on CircleCI, with build information organized by branch.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "projects",
      "item": [
        {
          "id": "f49da5c0-dde6-41de-bc1d-7fad8c6e2754",
          "name": "getProjects",
          "request": {
            "url": "http://circleci.com/api/v1/projects",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of all the projects you're following on CircleCI, with build information organized by branch"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed5e88a8-aa36-4759-90ed-86cca7c41e7d"
            }
          ]
        }
      ]
    }
  ]
}