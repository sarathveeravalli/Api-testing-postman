<h1 align="center" style="color:#0072C6;">🌍 API Testing with Postman 🚀</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Postman-API-orange?logo=postman" alt="Postman Badge">
  <img src="https://img.shields.io/badge/REST%20Countries-v3.1-blue?logo=restcountries">
  <img src="https://img.shields.io/badge/Status-Ready%20to%20Use-brightgreen">
</p>

---

## ✨ Overview

This repository provides a **Postman collection** for testing the [REST Countries API](https://restcountries.com/).  
Easily test `GET` endpoints for all countries or by country name!

---

## 📂 Files Included

| File Name                           | Description                                  |
|--------------------------------------|----------------------------------------------|
| `README.md`                         | This colorful documentation file 📘          |
| `api_testing.postman_collection.json`| Postman collection for API requests 📮        |

---

## 🎨 Features

- **Well-structured Postman collection**
- **Ready-to-use endpoints** for REST Countries API
- **Minimal setup required**
- **Colorful & user-friendly documentation**

---

## 📋 Endpoints in Collection

| Name                | Method | URL                                         | Description                |
|---------------------|--------|---------------------------------------------|----------------------------|
| Get All Countries   | GET    | `https://restcountries.com/v3.1/all`        | Returns all countries      |
| Get Country by Name | GET    | `https://restcountries.com/v3.1/name/india` | Returns data for 'India'   |

---

## 🚀 Getting Started

1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. **Import Postman Collection**  
   - Open [Postman](https://www.postman.com/)
   - Click `Import`
   - Select `api_testing.postman_collection.json`

3. **Send Requests!**  
   - Choose the desired endpoint and click **Send**!

---

## 📦 Example Response

<details>
  <summary><b>Get Country by Name</b></summary>

```json
[
  {
    "name": {
      "common": "India",
      "official": "Republic of India"
    },
    "cca2": "IN",
    "region": "Asia",
    "population": 1380004385
    // ...more fields
  }
]
```
</details>

---

## 🖍️ Color Legend

- <span style="color:#FFA500;"><b>Orange</b></span> : Postman/Requests
- <span style="color:#0072C6;"><b>Blue</b></span> : REST API/Endpoints
- <span style="color:#43A047;"><b>Green</b></span> : Ready to use/Status

---

## 🙌 Credits

- [REST Countries API](https://restcountries.com/)
- [Postman](https://www.postman.com/)

---

<p align="center" style="color:#0072C6;">
  <b>Happy Testing! 🌟</b>
</p>
