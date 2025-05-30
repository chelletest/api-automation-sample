# api-automation-sample with Postman & Newman

This is a basic API automation sample using Postman and Newman to test the **JSONPlaceholder** API.

## Description

- This project contains a **Postman collection** that tests a **GET request** to the endpoint `https://jsonplaceholder.typicode.com/posts/1`.
- It includes tests for verifying the status code and the title field in the response.

## Tools Used

- Postman (API testing)
- Newman (Postman’s CLI tool for automation)

## How to Run

1. Install **Newman**:
    ```bash
    npm install -g newman
    ```
2. Run the collection:
    ```bash
    newman run api-tests.postman_collection.json
    ```

## 🔗 Collection File

- **API Test Collection**: `api-tests.postman_collection.json`

---
<img width="818" alt="Terminal" src="https://github.com/user-attachments/assets/bc66fcc1-e45c-4035-82f3-b095262376d4" />

