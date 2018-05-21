{
  "info": {
    "name": "CircleCI Get Me",
    "_postman_id": "759ce23e-eb55-45a8-8547-f7b82cc98893",
    "description": "Provides information about the signed in user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Me",
      "item": [
        {
          "id": "8504be23-828c-4407-b17a-4c3e7139fa0c",
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
              "id": "adbe9a8d-ba26-4ab1-a9ad-8fedc5466224"
            }
          ]
        }
      ]
    }
  ]
}