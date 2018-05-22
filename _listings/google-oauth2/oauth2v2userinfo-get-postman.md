{
  "info": {
    "name": "Google OAuth2 APIs Get User Info",
    "_postman_id": "afef13cc-aeb2-47dc-8f69-02c9419cbab4",
    "description": "Get the user information for this session.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Certificate",
      "item": [
        {
          "id": "09bc3ba7-3d41-473c-b250-4580c2fe7846",
          "name": "oauth2.getCertForOpenIdConnect",
          "request": {
            "url": "http://www.googleapis.com/oauth2/v2/certs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the certification for this session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a13eec3-f387-4443-9808-29fd9f97fd33"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "764ec9ab-f098-4898-8d5c-b40918e65c61",
          "name": "oauth2.tokeninfo",
          "request": {
            "url": "http://www.googleapis.com/oauth2/v2/tokeninfo?access_token=%7B%7D&id_token=%7B%7D&token_handle=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Get the token information for this session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3db423a5-0920-46da-8c3c-1ce78c22e682"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "1e7c4575-d6f1-4c8d-b097-d9bcf7c6fae8",
          "name": "oauth2.userinfo.get",
          "request": {
            "url": "http://www.googleapis.com/oauth2/v2/userinfo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the user information for this session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39a41456-f293-468f-9b17-812d4578ce7e"
            }
          ]
        }
      ]
    }
  ]
}