# Rails Sample API

This is a lightweight, API-only Ruby on Rails project built for showcasing professional backend development skills using modern Rails conventions. It provides basic CRUD functionality for a \`User\` resource with clean code structure, Postman documentation, and ready-to-deploy configuration.

---

## 🚀 Tech Stack

- Ruby on Rails (API-only mode)
- PostgreSQL
- RSpec (Optional setup)
- Postman (Collection included)
- JSON-based REST API

---

## 📦 Features

- Clean RESTful API endpoints for \`User\` resource
- Namespaced versioned routes (\`/api/v1/users\`)
- JSON responses for API-only architecture
- Easy to extend for authentication, pagination, or filtering
- Postman collection provided for quick testing

---

## 📁 Folder Structure

\`\`\`
app/
 └── controllers/
     └── api/
         └── v1/
             └── users_controller.rb
db/
 └── migrate/
 └── seeds.rb
config/
 └── routes.rb
\`\`\`

---

## 🔧 Setup Instructions

### 1. Clone the repo
\`\`\`bash
git clone https://github.com/2017kamb/rails_sample_api.git
cd rails_sample_api
\`\`\`

### 2. Install dependencies
\`\`\`bash
bundle install
\`\`\`

### 3. Setup PostgreSQL database  
Edit \`config/database.yml\` if needed, then run:
\`\`\`bash
rails db:create db:migrate db:seed
\`\`\`

### 4. Start the server
\`\`\`bash
rails s
\`\`\`

---

## 📬 API Endpoints

| Method | Endpoint           | Description        |
|--------|--------------------|--------------------|
| GET    | /api/v1/users      | List all users     |
| GET    | /api/v1/users/:id  | Show single user   |
| POST   | /api/v1/users      | Create new user    |

---

## 🧪 Postman Collection

You can test the API using the provided Postman collection file:

📥 [Download Postman Collection](./postman/rails_sample_api.postman_collection.json)

Or import it directly into your Postman app.

---

## 📸 Sample JSON Output

\`\`\`json
[
  {
    "id": 1,
    "name": "Raj Kumar",
    "email": "raj@example.com",
    "created_at": "2025-06-28T04:00:00Z"
  }
]
\`\`\`

---

## 👨‍💻 Author

**Raj Kumar**  
Ruby on Rails Developer (10+ Years Experience)  
🔗 [LinkedIn](https://www.linkedin.com/in/2017kamb/)  
🔗 [GitHub](https://github.com/2017kamb)

---

## 📃 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
