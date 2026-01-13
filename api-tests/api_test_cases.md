# API Test Cases (Postman) — JSONPlaceholder

Base URL: https://jsonplaceholder.typicode.com

## TC-API-01 Get post by valid ID
Method: GET  
Endpoint: /posts/1  
Steps:
1. Send request
Expected:
- Status code: 200
- Content-Type: application/json
- Response has fields: userId, id, title, body

---

## TC-API-02 Get post by wrong ID
Method: GET  
Endpoint: /posts/999999  
Steps:
1. Send request
Expected:
- Status code: 404
- Response body: {}

---

## TC-API-03 Create post (valid body)
Method: POST  
Endpoint: /posts  
Body (JSON):
```json
{
  "title": "QA practice",
  "body": "Learning API testing",
  "userId": 1
}
