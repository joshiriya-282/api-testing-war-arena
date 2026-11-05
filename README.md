# api-testing-war-arena
Interactive REST API Testing Dashboard
# ⚔️ PROBE — API Testing War Arena

### Inspect the Request. Challenge the Response. Trust the Evidence.

PROBE is an interactive API testing practice environment designed to help developers understand REST API operations, inspect HTTP responses, and validate API behavior through automated test assertions.

Built as an interactive testing dashboard, PROBE provides a hands-on environment for practicing API testing using real HTTP requests against the JSONPlaceholder public sandbox API.

---

## 🚀 Project Overview

API testing plays an important role in ensuring that applications communicate correctly and return expected responses.

PROBE provides a visual testing environment where users can select predefined API requests, send HTTP methods, inspect response bodies and headers, and evaluate automated assertions.

The platform focuses on practical API testing concepts, including CRUD operations, response validation, and negative testing.

## ✨ Key Features

- **Interactive Request Builder:** Select and execute predefined API requests.
- **HTTP Methods:** Practice GET, POST, PATCH, and DELETE operations.
- **Response Inspector:** View API response bodies in formatted JSON.
- **HTTP Status Monitoring:** Inspect response status codes and messages.
- **Response Headers:** Examine HTTP response headers.
- **Performance Metrics:** View response time and response size.
- **Automated Assertions:** Validate API responses against predefined expectations.
- **Test Result Filtering:** Separate passed and failed assertions.
- **Request Search:** Search and filter requests by name or HTTP method.
- **Negative Testing:** Explore unknown endpoint behavior.
- **Copy Response:** Copy response data for further inspection.

## 🧪 API Testing Scenarios

PROBE includes six predefined testing scenarios:

| Scenario | HTTP Method | Endpoint | Purpose |
|---|---|---|---|
| List Posts | GET | `/posts` | Retrieve a collection |
| Get Post by ID | GET | `/posts/1` | Retrieve a specific resource |
| Create Post | POST | `/posts` | Create a test resource |
| Update Post | PATCH | `/posts/1` | Update a resource field |
| Delete Post | DELETE | `/posts/1` | Test delete operation |
| Unknown Endpoint | GET | `/probe_missing_resource` | Practice negative testing |

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure |
| CSS3 | UI styling and layout |
| JavaScript | Request handling and test logic |
| Fetch API | Sending HTTP requests |
| JSON | Request and response data |
| JSONPlaceholder | Public practice API |
| Git & GitHub | Version control |

## 🔗 API Used

**JSONPlaceholder**

Base URL: `https://jsonplaceholder.typicode.com`

JSONPlaceholder is a free public fake REST API used for testing and prototyping.

No API credentials are required.

## 📂 Project Structure

```text
ApiTestingWarArena/
│
├── index.html
├── style.css
├── search-fix.css
├── palette.css
├── script.js
└── README.md
```

## 💻 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/joshiriya-282/api-testing-war-arena.git
```

**Step 2: Navigate to the project directory**

```bash
cd api-testing-war-arena
```

**Step 3: Open the project**

Open `index.html` in your browser or use the Live Server extension in VS Code.

**Step 4: Start testing**

1. Select an API request.
2. Review the HTTP method and endpoint.
3. Check the request body if applicable.
4. Click **Send Request**.
5. Inspect the response body and headers.
6. Review automated test assertions.

## 🎯 Learning Outcomes

Through this project, I explored:

- REST API fundamentals.
- HTTP request methods.
- CRUD operations.
- JSON request and response structures.
- HTTP status codes.
- API response validation.
- Automated test assertions.
- Negative testing concepts.
- JavaScript Fetch API.
- Asynchronous JavaScript using async/await.

## 🔮 Future Enhancements

- Custom API endpoint support.
- User-defined request headers.
- Authentication testing.
- Custom test case creation.
- Test history and reporting.
- Advanced response validation.

## 👩‍💻 Developed By

**Riya Joshi**

BCA Student | Aspiring Developer

GitHub: [joshiriya-282](https://github.com/joshiriya-282)

---

⭐ If you find this project interesting, feel free to explore the repository!

**Built with curiosity, logic, and code.** ⚔️
