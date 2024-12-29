# Request Header Parser Microservice

This is a simple microservice that parses information from the request headers and returns it in a structured JSON format. It is built as part of the FreeCodeCamp Back End Development and APIs certification.

---

## **Features**

- Returns the client's IP address, preferred language, and system information based on request headers.
- Implements a RESTful API endpoint at `/api/whoami`.
- Lightweight and fast, built using **Node.js** and **Express.js**.

---

## **API Endpoint**

### **GET /api/whoami**
Responds with a JSON object containing the following keys:

- **`ipaddress`**: The IP address of the client.
- **`language`**: The client's preferred language as per the `Accept-Language` header.
- **`software`**: The client's system information from the `User-Agent` header.

---

### **Example Response**
Request:
```bash
GET /api/whoami
