# Conduit – API Testing Project (Postman)

## 📌 Project Overview
**Conduit** is a REST API–based blogging platform (RealWorld example application) that supports user authentication, article management, profiles, comments, and tags.

This repository contains a **complete API testing project**, focused on:
- Manual API testing
- Automated API tests implemented in **Postman**
- Test design for REST APIs
- Independent and reusable test scenarios

---

## 🎯 Testing Objectives
- Verify correctness of all exposed API endpoints
- Validate authentication and authorization mechanisms
- Ensure all API requests are fully **independent**
- Cover positive, negative, and edge-case scenarios
- Validate response structure, status codes, and error handling
- Demonstrate clean and maintainable API test architecture

---

## 🌐 API Under Test
- **Base URL:** `https://conduit.mate.academy/api/`

---

## 🧩 Scope of Testing

### ✅ Covered Modules
- **User**
  - Sign Up
  - Sign In
  - Get current user
  - Update user data (email, username, password, bio, image)
  - Authorization validation

- **Articles**
  - Create / Read / Update / Delete
  - Global feed
  - Personal feed
  - Filtering by tags
  - Authorization and ownership rules

- **Profiles**
  - Get profile details
  - Follow / Unfollow users

- **Comments**
  - Create comments
  - Retrieve comments
  - Delete comments
  - Permission and ownership validation

- **Tags**
  - Retrieve available tags

---

## 🧪 Testing Approach

### 🔹 Postman Collection Design
- One Postman collection organized into folders:
  - User
  - Articles
  - Profile
  - Comments
  - Tags
- Each request:
  - Can be executed independently
  - Creates its own preconditions using **Pre-request scripts**
  - Does not rely on execution order or environment state

---

### 🔁 Test Data Management
- Test data is generated dynamically:
  - Users
  - Articles
  - Comments
- Cleanup logic is implemented (e.g. deleting articles after tests)
- The collection can be executed repeatedly without polluting the database

---

## ⚙️ Variables & Configuration
- Collection-level variables:
  - `BASE_URL`
  - `username`, `username2`
  - `email`, `email2`
  - `password`
- The collection runs **without selecting an environment**

---

## 🧠 Pre-request Scripts & Reusability
Reusable helper functions are defined at the **collection level**, including:
- User registration
- User login
- Article creation
- Comment creation
- Article deletion
- Follow / unfollow user

These helpers are reused across requests to:
- Avoid code duplication
- Maintain request independence
- Improve readability and maintainability

---

## ✅ Test Coverage
Each request includes automated tests that validate:
- HTTP status codes
- Response time
- Response body structure and required fields
- Authorization and permission rules
- Validation and error messages for negative scenarios

All tests are clearly named and easy to understand.

---

## ❌ Negative Scenarios Covered
- Invalid and duplicate user registration data
- Invalid login credentials
- Missing or incorrect authorization headers
- Unauthorized and forbidden operations
- Data validation edge cases

---

## 🐞 Bug Reporting
- Issues identified during testing were reported in **Jira**
- Bug reports include:
  - Reproduction steps
  - Expected vs actual results
  - Affected endpoint and request details

---

## 🔧 Tools Used
- **Postman** – API testing and automation
- **JavaScript** – pre-request scripts and assertions
- **Jira** – bug tracking
- **REST API** – backend testing

---

## ⏱️ Execution
- The Postman collection was executed multiple times
- All requests passed successfully
- Tests are repeatable and stable

---

## 📊 Key QA Takeaways
- Strong understanding of REST API testing
- Practical experience with Postman automation
- Clean and reusable test design
- Focus on authorization, validation, and edge cases
- Production-style approach to backend testing

---

## 👤 Author
**Bartosz Dąbek**  
QA Engineer

Focus areas:
- API Testing
- Postman
- Test Design
- REST
- Jira

---

## 📎 Notes
This repository is intended as a **portfolio API testing project**, demonstrating real-world backend QA practices.
