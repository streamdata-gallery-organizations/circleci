{
  "info": {
    "name": "CircleCI Get Recent Builds",
    "_postman_id": "534c5711-1abb-40c5-8aae-8e96b163d23b",
    "description": "Build summary for each of the last 30 recent builds, ordered by build_num.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "recent",
      "item": [
        {
          "id": "060d6574-7337-4264-a241-d340f4e661c4",
          "name": "getRecentBuilds",
          "request": {
            "url": "http://circleci.com/api/v1/recent-builds?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Build summary for each of the last 30 recent builds, ordered by build_num"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b090bc60-b326-4a52-9be8-c469ccad5a7a"
            }
          ]
        }
      ]
    }
  ]
}