# 🖥️ Request Header Parser Microservice

## 📌 Project Overview
This is a **Request Header Parser Microservice** built for FreeCodeCamp's Back End Development and APIs certification. It extracts information from request headers and returns a JSON response containing:

- 🌍 **IP Address** (`ipaddress` key)
- 🗣️ **Preferred Language** (`language` key)
- 💻 **Software Details** (`software` key)

## 🚀 How It Works
1. A client sends a request to `/api/whoami`.
2. The server extracts relevant data from the request headers.
3. A JSON response is returned with the extracted details.

## 🛠️ Technologies Used
- **Node.js** 🌱
- **Express.js** ⚡

## 🏗️ Setup & Installation
### Prerequisites
Ensure you have **Node.js** installed on your system.

### Steps to Run Locally
```sh
# Clone this repository
git clone <your-repo-url>

# Navigate into the project directory
cd request-header-parser

# Install dependencies
npm install

# Start the server
npm start
```
The microservice will be accessible at `http://localhost:3000/api/whoami`.

## 📡 API Endpoint
### `GET /api/whoami`
Returns a JSON response with:
```json
{
  "ipaddress": "192.168.1.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
}
```

## 📝 License
This project is licensed under the **MIT License**.

---
🚀 Built for FreeCodeCamp's Back End Development and APIs Certification. 🎓

