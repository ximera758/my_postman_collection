# My Postman API Collection

## 🚀 Overview

This repository contains a Postman collection demonstrating API testing skills.

The tests include:
- HTTP status codes validation
- Response body assertions
- API endpoint workflows
- Authentication scenarios (if applicable)

my_postman_collection/
├── My Postman Collection.json
└── README.md

## 🛠 Tools Used

- **Postman** — API testing
- **Postman Collection Export**
- (Optional) Newman for CLI execution

## 🧪 Running Tests Locally

### 1️⃣ Through Postman

1. Open Postman  
2. Import the collection file `My Postman Collection.json`  
3. Run the collection using Runner  
4. Validate tests

### 2️⃣ Through Newman (CLI)

If you have Newman installed:

```bash
npm install -g newman
Then run:
newman run "My Postman Collection.json"
🧠 What is tested

Expected HTTP response codes (200, 400, etc.)

Body values for specific endpoints

Sequence of requests (flows)

Error handling for invalid requests

📌 Notes

You can easily extend this collection with environment variables, pre-request scripts, and test scripts.
## 📦 Contents
