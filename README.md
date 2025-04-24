# 📈 StockManager: Stock Portfolio Management System

**StockManager** is a Spring Boot-based RESTful API that enables users to manage their stock market portfolio through full CRUD (Create, Read, Update, Delete) operations. It integrates real-time data validation and optimized querying using GraphQL and web scraping via JSoup.

---

## 🔧 Technologies & Tools

- **Java** — Core language for application logic.
- **Spring Boot** — Framework for building RESTful APIs quickly and efficiently.
- **JPA Repository** — Simplifies database interaction and data persistence.
- **REST API** — Enables structured and scalable data operations.
- **GraphQL** — Used for precise, memory-efficient data querying.
- **JSoup** — HTML parser for validating stock entries via web scraping.

---

## 📚 Key Features

- **Portfolio Management via REST API**  
  Perform essential operations using standard HTTP methods:
  - `GET` — Retrieve stock data
  - `POST` — Add new stock to the portfolio
  - `PUT` — Update stock details
  - `DELETE` — Remove stock from the portfolio

- **Efficient Data Queries using GraphQL**  
  Query only required fields to reduce data load and memory consumption compared to traditional SQL queries.

- **Real-Time Stock Validation with JSoup**  
  - Ensures only valid stocks are added to the portfolio.
  - Scrapes live data from a stock market website to verify the stock symbol.
  - Invalid or delisted stocks are automatically excluded during creation or updates.

---

## 🚀 Getting Started

Follow these steps to run the project locally:

1. **Open the project** in your preferred IDE (IntelliJ / Eclipse).
2. **Run the application** as a Spring Boot project.
3. **Use Postman** (or any API testing tool) to interact with the endpoints:
   - Choose the correct HTTP method (`GET`, `POST`, `PUT`, `DELETE`).
   - Use JSON format for request bodies in `POST` and `PUT` methods.
4. **To make GraphQL queries**:
   - Use Postman's GraphQL tab or any GraphQL client.
   - Ensure the query syntax is correct and targets only necessary fields.

📌 **Note**: Ensure your local server is running before sending any API requests.

---

## ✅ Project Benefits

- Promotes clean architecture and modular development practices.
- Combines traditional REST with modern tools like GraphQL and JSoup.
- Ensures data accuracy by validating stock entries before saving.
- Suitable for both academic and pre-production-level learning and demonstration.

---

For suggestions, improvements, or collaborations, feel free to reach out.

---

